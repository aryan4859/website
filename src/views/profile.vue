<template>
  <div class="profile-container10">
    <header-full></header-full>
    <div class="profile-profile">
      <img alt="image" src="/bruce-mars-200h.jpg" class="profile-image1" />
      <div class="profile-container11">
        <div class="profile-container12">
          <h4 class="profile-text10">Michael Roven</h4>
          <outline-blue-button button="follow"></outline-blue-button>
        </div>
        <div class="profile-container13">
          <span class="profile-text11">
            <span class="profile-text12">323</span>
            <span>Posts</span>
          </span>
          <span class="profile-text14">
            <span class="profile-text15">3.5k</span>
            <span>Followers</span>
          </span>
          <span>
            <span class="profile-text18">260</span>
            <span>Following</span>
          </span>
        </div>
        <span class="Medium">
          Decisions: If you can’t decide, the answer is no. If two equally
          difficult paths, choose the one more painful in the short term (pain
          avoidance is creating an illusion of equality). Choose the path that
          leaves you more equanimous.
        </span>
        <next-button button="More about me"></next-button>
      </div>
    </div>
    <div class="profile-blog-posts">
      <h1 class="profile-text21 HeadingTwo">
        <span></span>
        <span>Check my latest blogposts</span>
        <br />
      </h1>
      <div class="profile-container14">
        <blog-card></blog-card>
        <blog-card
          imageSrc="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/soft-ui-design-system/assets/img/color-clock.jpg"
          description="Venture investment in U.S. startups rose sequentially in the second quarter of 2017, boosted by large, ate-stage financings"
        ></blog-card>
        <blog-card
          title="MateLabs machine learning"
          imageSrc="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/soft-ui-design-system/assets/img/color-wall.jpg"
          description="If you’ve ever wanted to train a machine learning model and integrate it with IFTTT, you now can with"
        ></blog-card>
        <div class="profile-container15">
          <div class="profile-card">
            <div class="profile-container16">
              <h1 class="profile-text24">Flexible work hours</h1>
              <span class="profile-text25">
                <span class="profile-text26">
                  Rather than worrying about switching offices every couple years,
                  you stay in the same place.
                </span>
              </span>
              <div class="profile-container17">
                <button class="profile-button button">
                  <span class="profile-text27">Read more</span>
                  <svg viewBox="0 0 1024 1024" class="profile-icon10">
                    <path
                      d="M512 170l342 342-342 342-60-60 238-240h-520v-84h520l-238-240z"
                    ></path>
                  </svg>
                </button>
              </div>
            </div>
            <div class="profile-container18"></div>
          </div>
        </div>
      </div>
    </div>
    <div class="profile-contact">
      <div class="profile-container19">
        <div class="profile-form1">
          <h2 class="profile-text28 HeadingOne"><span>Say Hi!</span></h2>
          <span class="profile-text30 Lead">
            We&apos;d like to talk with you.
          </span>
          <form class="profile-form2">
            <label class="profile-text31 Label">My name is</label>
            <input
              type="text"
              placeholder="Full Name"
              class="profile-textinput1 Small input"
            />
            <label class="profile-text32 Label">I&apos;m looking for</label>
            <input
              type="text"
              placeholder="What you love"
              class="profile-textinput2 Small input"
            />
            <label class="profile-text33 Label">Your message</label>
            <textarea
              rows="8"
              placeholder="I want to say that..."
              class="profile-textarea textarea Small"
            ></textarea>
          </form>
          <div class="profile-container20">
            <div class="profile-container21">
              <primary-blue-button button="send message"></primary-blue-button>
            </div>
          </div>
        </div>
        <div class="profile-info">
          <div class="profile-container22">
            <h3 class="HeadingTwo">
              <span>
                Contact
                <span v-html="raw7n0m"></span>
              </span>
              <span>Information</span>
            </h3>
            <span class="profile-text37">
              Fill up the form and our Team will get back to you within 24 hours.
            </span>
            <div class="profile-container23">
              <div class="profile-container24">
                <svg viewBox="0 0 1024 1024" class="profile-icon12">
                  <path
                    d="M742 460l-94-94q-18-18-10-44 24-72 24-152 0-18 12-30t30-12h150q18 0 30 12t12 30q0 300-213 513t-513 213q-18 0-30-12t-12-30v-150q0-18 12-30t30-12q80 0 152-24 24-10 44 10l94 94q186-96 282-282z"
                  ></path>
                </svg>
                <a href="tel:+40 772 100 200" class="profile-link1 Small">
                  (+40) 772 100 200
                </a>
              </div>
              <div class="profile-container25">
                <svg viewBox="0 0 1024 1024" class="profile-icon14">
                  <path
                    d="M854 342v-86l-342 214-342-214v86l342 212zM854 170q34 0 59 26t25 60v512q0 34-25 60t-59 26h-684q-34 0-59-26t-25-60v-512q0-34 25-60t59-26h684z"
                  ></path>
                </svg>
                <a
                  href="mailto:hello@creative-tim.com?subject="
                  class="profile-link2 Small"
                >
                  hello@creative-tim.com
                </a>
              </div>
              <div class="profile-container26">
                <svg viewBox="0 0 1024 1024" class="profile-icon16">
                  <path
                    d="M512 490q44 0 75-31t31-75-31-75-75-31-75 31-31 75 31 75 75 31zM512 86q124 0 211 87t87 211q0 62-31 142t-75 150-87 131-73 97l-32 34q-12-14-32-37t-72-92-91-134-71-147-32-144q0-124 87-211t211-87z"
                  ></path>
                </svg>
                <span class="profile-text38 Small">
                  Dyonisie Wolf Bucharest, RO 010458
                </span>
              </div>
            </div>
            <div class="profile-container27">
              <svg viewBox="0 0 877.7142857142857 1024" class="profile-icon18">
                <path
                  d="M713.143 73.143c90.857 0 164.571 73.714 164.571 164.571v548.571c0 90.857-73.714 164.571-164.571 164.571h-107.429v-340h113.714l17.143-132.571h-130.857v-84.571c0-38.286 10.286-64 65.714-64l69.714-0.571v-118.286c-12-1.714-53.714-5.143-101.714-5.143-101.143 0-170.857 61.714-170.857 174.857v97.714h-114.286v132.571h114.286v340h-304c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571z"
                ></path></svg
              ><svg viewBox="0 0 950.8571428571428 1024" class="profile-icon20">
                <path
                  d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                ></path></svg
              ><svg viewBox="0 0 877.7142857142857 1024" class="profile-icon22">
                <path
                  d="M585.143 857.143c-5.714-33.143-27.429-147.429-80-284.571-0.571 0-1.714 0.571-2.286 0.571 0 0-222.286 77.714-294.286 234.286-3.429-2.857-8.571-6.286-8.571-6.286 65.143 53.143 148 85.714 238.857 85.714 52 0 101.143-10.857 146.286-29.714zM479.429 510.286c-9.143-21.143-19.429-42.286-30.286-63.429-193.143 57.714-378.286 53.143-384.571 53.143-0.571 4-0.571 8-0.571 12 0 96 36.571 184 96 250.286v0c102.286-182.286 304.571-247.429 304.571-247.429 5.143-1.714 10.286-2.857 14.857-4.571zM418.286 389.143c-65.143-115.429-134.286-209.143-139.429-216-104.571 49.143-182.286 145.714-206.857 261.714 9.714 0 166.286 1.714 346.286-45.714zM809.143 571.429c-8-2.286-112.571-35.429-233.714-16.571 49.143 135.429 69.143 245.714 73.143 268 84-56.571 143.429-146.857 160.571-251.429zM349.143 148c-0.571 0-0.571 0-1.143 0.571 0 0 0.571-0.571 1.143-0.571zM686.286 230.857c-65.714-58.286-152.571-93.714-247.429-93.714-30.286 0-60 4-88.571 10.857 5.714 7.429 76.571 100.571 140.571 218.286 141.143-52.571 194.286-133.714 195.429-135.429zM813.714 508c-1.143-88.571-32.571-170.286-85.143-234.286-1.143 1.143-61.143 88-209.143 148.571 8.571 17.714 17.143 36 25.143 54.286 2.857 6.286 5.143 13.143 8 19.429 129.143-16.571 256.571 11.429 261.143 12zM877.714 512c0 242.286-196.571 438.857-438.857 438.857s-438.857-196.571-438.857-438.857 196.571-438.857 438.857-438.857 438.857 196.571 438.857 438.857z"
                ></path></svg
              ><svg viewBox="0 0 877.7142857142857 1024" class="profile-icon24">
                <path
                  d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
                ></path>
              </svg>
            </div>
          </div>
          <img alt="image" src="/wave-1.svg" class="profile-image2" />
          <div class="profile-container28"></div>
        </div>
      </div>
    </div>
    <app-footer></app-footer>
  </div>
</template>

<script>
import HeaderFull from '../components/header-full'
import OutlineBlueButton from '../components/outline-blue-button'
import NextButton from '../components/next-button'
import BlogCard from '../components/blog-card'
import PrimaryBlueButton from '../components/primary-blue-button'
import AppFooter from '../components/footer'

export default {
  name: 'Profile',
  props: {},
  components: {
    HeaderFull,
    OutlineBlueButton,
    NextButton,
    BlogCard,
    PrimaryBlueButton,
    AppFooter,
  },
  data() {
    return {
      raw7n0m: ' ',
    }
  },
  metaInfo: {
    title: 'Profile - Soft UI Pro',
    meta: [
      {
        property: 'og:title',
        content: 'Profile - Soft UI Pro',
      },
    ],
  },
}
</script>

<style scoped>
.profile-container10 {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.profile-profile {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  max-width: 1320px;
  margin-top: var(--dl-space-space-sixunits);
  align-items: flex-start;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-sixunits);
}
.profile-image1 {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius75);
}
.profile-container11 {
  flex: 2;
  display: flex;
  align-items: flex-start;
  margin-left: var(--dl-space-space-sixunits);
  margin-right: var(--dl-space-space-sixunits);
  flex-direction: column;
}
.profile-container12 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-halfunit);
  flex-direction: row;
  justify-content: space-between;
}
.profile-text10 {
  color: var(--dl-color-secondary-700);
  font-size: 1.5rem;
  font-style: normal;
  margin-bottom: var(--dl-space-space-halfunit);
}
.profile-container13 {
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.profile-text11 {
  margin-right: var(--dl-space-space-unit);
}
.profile-text12 {
  color: var(--dl-color-secondary-700);
  font-style: normal;
  font-weight: 600;
}
.profile-text14 {
  margin-right: var(--dl-space-space-unit);
}
.profile-text15 {
  color: var(--dl-color-secondary-700);
  font-style: normal;
  font-weight: 600;
}
.profile-text18 {
  color: var(--dl-color-secondary-700);
  font-style: normal;
  font-weight: 600;
}
.profile-blog-posts {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  max-width: 1320px;
  align-items: flex-start;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-doubleunit);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
}
.profile-text21 {
  color: var(--dl-color-secondary-500);
  margin-left: var(--dl-space-space-unit);
  margin-right: var(--dl-space-space-unit);
}
.profile-container14 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: stretch;
  flex-direction: row;
  justify-content: space-between;
}
.profile-container15 {
  flex: 1;
  margin: var(--dl-space-space-unit);
  display: flex;
  align-items: stretch;
  flex-direction: row;
  justify-content: flex-start;
}
.profile-card {
  flex: 1;
  width: 255px;
  display: flex;
  padding: var(--dl-space-space-unitandahalfunit);
  position: relative;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-radius1);
  flex-direction: column;
  background-size: cover;
  background-image: url("https://raw.githubusercontent.com/creativetimofficial/public-assets/master/soft-ui-design-system/assets/img/seaside.jpg");
}
.profile-container16 {
  display: flex;
  z-index: 2;
  align-items: flex-start;
  flex-direction: column;
}
.profile-text24 {
  color: var(--dl-color-gray-white);
  margin-top: var(--dl-space-space-halfunit);
  margin-bottom: var(--dl-space-space-halfunit);
}
.profile-text25 {
  color: var(--dl-color-gray-white);
  margin-top: var(--dl-space-space-unit);
  margin-bottom: var(--dl-space-space-unit);
}
.profile-text26 {
  display: inline;
  font-weight: 400;
  white-space: normal;
}
.profile-container17 {
  display: flex;
  position: relative;
}
.profile-button {
  color: var(--dl-color-blue-500);
  display: flex;
  padding-top: var(--dl-space-space-halfunit);
  border-width: 0px;
  padding-left: 0px;
  padding-right: 0px;
  flex-direction: row;
  padding-bottom: var(--dl-space-space-halfunit);
  background-color: transparent;
}
.profile-text27 {
  color: var(--dl-color-gray-white);
  margin-right: var(--dl-space-space-halfunit);
}
.profile-icon10 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
}
.profile-container18 {
  top: auto;
  flex: 0 0 auto;
  left: 0px;
  right: auto;
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  bottom: 0px;
  height: 100%;
  display: flex;
  position: absolute;
  margin-top: var(--dl-space-space-unit);
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-radius1);
  flex-direction: column;
  background-color: rgba(0,0,0,.4);
}
.profile-contact {
  width: 100%;
  max-width: 1320px;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  padding-bottom: var(--dl-space-space-sixunits);
}
.profile-container19 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  box-shadow: 0 20px 27px 0 rgb(0 0 0 / 5%);
  align-items: stretch;
  border-radius: var(--dl-radius-radius-radius1);
  flex-direction: row;
  background-color: var(--dl-color-gray-white);
}
.profile-form1 {
  flex: 5;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-doubleunit);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
}
.profile-text28 {
  color: var(--dl-color-secondary-500);
  margin-bottom: var(--dl-space-space-unit);
}
.profile-text30 {
  margin-bottom: var(--dl-space-space-doubleunit);
}
.profile-form2 {
  flex: 1;
  width: 100%;
  display: flex;
  flex-direction: column;
}
.profile-text31 {
  color: var(--dl-color-secondary-500);
  margin-top: var(--dl-space-space-unit);
  margin-bottom: var(--dl-space-space-halfunit);
}
.profile-textinput1 {
  width: 100%;
  height: 40px;
  transition: 0.3s;
  padding-top: var(--dl-space-space-halfunit);
  border-color: var(--dl-color-secondary-100);
  padding-left: var(--dl-space-space-triplequarterunit);
  border-radius: var(--dl-radius-radius-radius5);
  padding-right: var(--dl-space-space-triplequarterunit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.profile-textinput1:focus {
  outline: 0;
  box-shadow: 0 0 0 2px #e9aede;
  border-color: var(--dl-color-pink-200);
}
.profile-text32 {
  color: var(--dl-color-secondary-500);
  margin-top: var(--dl-space-space-unit);
  margin-bottom: var(--dl-space-space-halfunit);
}
.profile-textinput2 {
  width: 100%;
  height: 40px;
  transition: 0.3s;
  padding-top: var(--dl-space-space-halfunit);
  border-color: var(--dl-color-secondary-100);
  padding-left: var(--dl-space-space-triplequarterunit);
  border-radius: var(--dl-radius-radius-radius5);
  padding-right: var(--dl-space-space-triplequarterunit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.profile-textinput2:focus {
  outline: 0;
  box-shadow: 0 0 0 2px #e9aede;
  border-color: var(--dl-color-pink-200);
}
.profile-text33 {
  color: var(--dl-color-secondary-500);
  margin-top: var(--dl-space-space-unit);
  margin-bottom: var(--dl-space-space-halfunit);
}
.profile-textarea {
  width: 100%;
  transition: 0.3s;
  padding-top: var(--dl-space-space-halfunit);
  border-color: var(--dl-color-secondary-100);
  padding-left: var(--dl-space-space-triplequarterunit);
  border-radius: var(--dl-radius-radius-radius5);
  padding-right: var(--dl-space-space-triplequarterunit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.profile-textarea:focus {
  outline: 0;
  box-shadow: 0 0 0 2px #e9aede;
  border-color: var(--dl-color-pink-200);
}
.profile-container20 {
  display: flex;
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
  align-items: flex-start;
  flex-direction: column;
}
.profile-container21 {
  display: flex;
}
.profile-info {
  flex: 4;
  color: var(--dl-color-gray-white);
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  padding-left: var(--dl-space-space-sixunits);
  border-radius: 0px;
  flex-direction: column;
  background-size: cover;
  justify-content: center;
  background-image: url("../../public/curved5-1400w.jpg");
  border-top-right-radius: var(--dl-radius-radius-radius1);
  border-bottom-right-radius: var(--dl-radius-radius-radius1);
}
.profile-container22 {
  display: flex;
  padding: var(--dl-space-space-fourunits);
  z-index: 1;
  align-items: flex-start;
  flex-direction: column;
}
.profile-text37 {
  opacity: 0.8;
}
.profile-container23 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: column;
}
.profile-container24 {
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.profile-icon12 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-unit);
}
.profile-link1 {
  opacity: 0.8;
  text-decoration: none;
}
.profile-container25 {
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.profile-icon14 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-unit);
}
.profile-link2 {
  opacity: 0.8;
  text-decoration: none;
}
.profile-container26 {
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.profile-icon16 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-unit);
}
.profile-text38 {
  opacity: 0.8;
}
.profile-container27 {
  flex: 0 0 auto;
  width: 200px;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.profile-icon18 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-doubleunit);
}
.profile-icon20 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-doubleunit);
}
.profile-icon22 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-doubleunit);
}
.profile-icon24 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-doubleunit);
}
.profile-image2 {
  top: 0px;
  left: -1px;
  right: auto;
  width: 100px;
  z-index: 2;
  position: absolute;
  object-fit: cover;
}
.profile-container28 {
  top: auto;
  left: auto;
  right: 0px;
  width: 100%;
  bottom: 0px;
  height: 100%;
  opacity: 0.9;
  position: absolute;
  background-image: linear-gradient(310deg,#2152ff,#21d4fd);
}
@media(max-width: 991px) {
  .profile-container11 {
    margin-left: var(--dl-space-space-tripleunit);
    margin-right: var(--dl-space-space-tripleunit);
  }
  .profile-container15 {
    width: 100%;
  }
  .profile-card {
    width: 100%;
  }
  .profile-container19 {
    flex-direction: column;
  }
  .profile-info {
    padding-left: 0px;
    border-top-right-radius: 0;
    border-bottom-left-radius: var(--dl-radius-radius-radius1);
  }
  .profile-image2 {
    display: none;
  }
}
@media(max-width: 767px) {
  .profile-profile {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .profile-container11 {
    margin-left: 0px;
    margin-right: 0px;
  }
  .profile-container12 {
    margin-top: var(--dl-space-space-unit);
    margin-bottom: var(--dl-space-space-unit);
  }
  .profile-text10 {
    margin-top: var(--dl-space-space-unit);
  }
  .profile-blog-posts {
    padding-top: var(--dl-space-space-doubleunit);
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
    padding-bottom: var(--dl-space-space-doubleunit);
  }
  .profile-container15 {
    margin-top: var(--dl-space-space-doubleunit);
  }
  .profile-contact {
    padding-top: var(--dl-space-space-doubleunit);
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
    padding-bottom: var(--dl-space-space-doubleunit);
  }
  .profile-form1 {
    padding-top: var(--dl-space-space-doubleunit);
  }
}
</style>
