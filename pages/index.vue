<template>
  <div>
    <div class="main-section">
      <div class="section">
        <div class="section-left">
          <img src="/images/main.png" />
          <div class="arrow bounce"></div>
        </div>

        <div class="section-right">
          <p>
            At <b>civiso</b>, we are bringing it one step closer by bridging
            students' unique passions with civic and humanitarian engagement
            through nonprofit incubation, project development, and civil
            discourse.
          </p>
        </div>
      </div>
    </div>
    <div class="section">
      <div class="section-heading">
        <h1>Our Departments.</h1>
        <p>How Civiso is getting its message across</p>
      </div>
      <div class="department">
        <div class="image-containers">
          <div class="image-comp spacing">
            <img src="images/department/first.png" />
            <div class="card">
              <h2>Projects.</h2>
              <p>
                We pair our members with industry professionals and give them
                the means to research the issues that they feel strongly about.
                With the team at Civiso, you can learn data analysis, data
                visualization, research protocols, advance policy work, and much
                more.
              </p>
            </div>
          </div>
          <div class="image-comp">
            <img src="images/department/third.png" />
            <div class="card">
              <h2>Growth & Marketing.</h2>
              <p>
                Our Social Media team is actively involved with all platforms
                including Instagram, TikTok, & others! We design, produce, &
                curate content meant to incite change, & make research
                infographics that put injustice into perspective.
              </p>
            </div>
          </div>
        </div>

        <div class="image-containers">
          <div class="image-comp spacing">
            <img src="images/department/fourth.png" class="fourth" />
            <div class="card">
              <h2>Web Development.</h2>
              <p>
                Our Web Development team keeps our site up & running, and keeps
                you informed on the latest news in youth activism. All their
                efforts behind the scenes make it possible for Civiso’s
                interface to run smoothly, and for the public to be educated.
              </p>
            </div>
          </div>
          <div class="image-comp">
            <img src="images/department/second.png" />
            <div class="card">
              <h2>Internal Relations.</h2>
              <p>
                Our professional partnerships in many industries allow us to
                have access to platforms for civil discourse. The foundation of
                our efforts relies on our own preparation. Thus, Civiso is
                intent on constantly educating & informing its members.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="section">
      <div class="section-heading">
        <h1>Our Partners & Affiliates.</h1>
        <p>The team at Civiso has the active support of faculty from</p>
      </div>
      <AffiliatesSlider />
    </div>

    <div class="section">
      <div class="section-heading">
        <h1>Civiso: <span class="highlight">Inspired.</span></h1>
        <p>Calls to action written by our very own members</p>
      </div>

      <div class="calls">
        <div class="calls-images">
          <img src="/images/calls/calls-1.png" />
          <img src="/images/calls/calls-2.png" />
          <img src="/images/calls/calls-3.png" />
        </div>
      </div>
    </div>

    <div class="section">
      <div class="section-heading">
        <h1>Civiso: <span class="highlight">Toks.</span></h1>
        <p>Raising awareness in 60 seconds or less.</p>
      </div>
      <br />
    </div>
  </div>
</template>

<script>
import AffiliatesSlider from "../components/AffiliatesSlider";
export default {
  components: { AffiliatesSlider },
};
</script>

<style lang="scss">
.section {
  margin: 6rem 0;
}

.section-heading {
  h1 {
    margin-bottom: 0.75rem;
  }

  margin-bottom: 2rem;
}

.department {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-content: center;
  margin-top: 3rem;
  margin-bottom: 2rem;

  img {
    width: 300px;
  }
}

.calls {
  padding-top: 2rem;

  .calls-images {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-content: flex-start;
  }
}

.main-section {
  padding-top: 7rem;
  padding-bottom: 2rem;

  .section {
    display: flex;
    flex-direction: row;
    padding: 0 2rem;
    height: 100%;

    .section-left img {
      height: 210px;
    }

    .section-right {
      text-align: center;
      display: flex;
      align-items: center;
      padding: 0 1.5rem;

      p {
        line-height: 1.3;
        font-weight: 300;
        font-size: 1.3rem;
      }
    }
  }
}

.arrow {
  position: relative;
  bottom: -4rem;
  left: 50%;
  margin-left: -20px;
  width: 40px;
  height: 40px;

  background-image: url("static/images/arrow.png");
  background-repeat: no-repeat;
  background-size: contain;
}

.bounce {
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0%,
  20%,
  50%,
  80%,
  100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-30px);
  }
  60% {
    transform: translateY(-15px);
  }
}

.image-containers {
  margin: auto;
}

.spacing {
  margin-bottom: 4rem;
}

.card {
  background: rgba(243, 243, 243, 1);
  width: 300px;
  border-top: 4px solid #f5a201;
  border-bottom: 4px solid #f5a201;
  padding: 2rem 1rem;
  text-align: center;

  h2 {
    color: #f5a201;
    padding-bottom: 1rem;
  }
}
.image-comp spacing {
  position: relative;
  size: 50%;
}
.image-comp {
  position: relative;

  .card {
    position: absolute;
    top: 20px;
    left: 20px;
    transition: 0.3s;

    &:hover {
      left: 40px;
      top: -10px;
    }
  }
}
.fourth {
  max-height: 340.91px;
}
</style>
