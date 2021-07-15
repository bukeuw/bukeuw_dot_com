<template>
  <div class="container row">
    <div class="card col-8 mx-auto p-0 flex-row">
      <div class="col-5 bg-dark text-white">
        <div class="avatar rounded-circle mx-auto mt-3" />

        <div class="contact text-left mt-4 px-5">
          <p class="font-weight-bold mb-1">
            CONTACT
          </p>
          <p class="mb-1">
            <i class="fa fa-envelope" /> <a class="text-white" href="mailto:ato@bukeuw.com">ato@bukeuw.com</a>
          </p>
          <p>
            <i class="fa fa-map-marker-alt" /> Jakarta, Indonesia
          </p>
        </div>
      </div>
      <div class="col-7 pt-3">
        <div class="job-desc mb-5">
          <h2 class="mb-0">
            Santo Blasius
          </h2>
          <p class="sub-title">
            Web Developer
          </p>
        </div>

        <div class="experiences text-left mb-4">
          <h5>Work Experience</h5>

          <div class="item row">
            <div class="col">
              <p class="font-weight-bold mb-0">
                Web Developer
              </p>
              <p class="text-muted">
                PT Erakomp Infonusa
              </p>
            </div>
            <div class="col">
              <p class="float-right text-muted">
                2019 - 2021
              </p>
            </div>
          </div>
        </div>

        <div class="skills text-left mb-4">
          <h5>Skill</h5>

          <div class="item row">
            <p class="col-4">
              Javascript

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-warning" style="width: 85%" />
              </span>
            </p>
            <p class="col-4">
              Vuejs

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-success" style="width: 75%" />
              </span>
            </p>
            <p class="col-4">
              Nuxt

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-success" style="width: 70%" />
              </span>
            </p>
            <p class="col-4">
              PHP

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-info" style="width: 80%" />
              </span>
            </p>
            <p class="col-4">
              Laravel

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-danger" style="width: 75%" />
              </span>
            </p>
            <p class="col-4">
              Phpunit

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-info" style="width: 55%" />
              </span>
            </p>
            <p class="col-4">
              Git

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-danger" style="width: 85%" />
              </span>
            </p>
            <p class="col-4">
              Docker

              <span class="progress" style="height: 5px">
                <div class="progress-bar bg-dark" style="width: 65%" />
              </span>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.avatar {
  width: 100px;
  height: 100px;
  background: url(~/assets/images/profile.jpg) center center;
  background-size: contain;
  background-repeat: no-repeat;
  background-color: #958f83;
}
</style>
