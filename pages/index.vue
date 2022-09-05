<template>
  <div>
    <!-- Container for demo purpose -->
    <div class="container my-5">

      <!--Section: Design Block-->
      <section class="mb-5">
        <div class="row">
          <div class="col-md-6 col-lg-7 col-xl-8 mb-4">
            <div class="bg-image rounded-6">
              <img class="w-100" src="https://mdbootstrap.com/img/new/blog/37.jpg"
                style="object-fit: cover; height: 421px" alt="Alternative text" />
              <a href="#!">
                <div class="mask" style="
              background: linear-gradient(
                to bottom,
                hsla(0, 0%, 0%, 0),
                hsla(0, 0%, 0%, 0.6)
              );
            ">
                  <div class="bottom-0 d-flex align-items-end h-100 p-4 text-white">
                    <div>
                      <div class="d-flex flex-row small">
                        <p class="text-uppercase">
                          <a href="#!" class="text-reset">Sport</a>
                        </p>
                        <p class="mx-2">•</p>
                        <p>06/27/2022</p>
                      </div>
                      <h5 class="fw-bold pb-1">
                        World Championships Budapest 2022: Swimming results, day 8.
                      </h5>
                      <p class="small mb-0">
                        By <a href="#!" class="text-reset">Janice Marray</a>
                      </p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-6 col-lg-5 col-xl-4 mb-4">
            <div class="bg-image rounded-6">
              <img class="w-100" src="https://mdbootstrap.com/img/new/blog/38.jpg"
                style="object-fit: cover; height: 421px" alt="Alternative text" />
              <a href="#!">
                <div class="mask" style="
              background: linear-gradient(
                to bottom,
                hsla(0, 0%, 0%, 0),
                hsla(0, 0%, 0%, 0.6)
              );
            ">
                  <div class="bottom-0 d-flex align-items-end h-100 p-4 text-white">
                    <div>
                      <div class="d-flex flex-row small">
                        <p class="text-uppercase">
                          <a href="#!" class="text-reset">Events</a>
                        </p>
                        <p class="mx-2">•</p>
                        <p>06/25/2022</p>
                      </div>
                      <h5 class="fw-bold pb-1">Equality and friendly events near you.</h5>
                      <p class="small mb-0">
                        By <a href="#!" class="text-reset">Danny Fisher</a>
                      </p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 col-lg-5 col-xl-4 mb-4">
            <div class="bg-image rounded-6">
              <img class="w-100" src="https://mdbootstrap.com/img/new/blog/41.jpg"
                style="object-fit: cover; height: 421px" alt="Alternative text" />
              <a href="#!">
                <div class="mask" style="
              background: linear-gradient(
                to bottom,
                hsla(0, 0%, 0%, 0),
                hsla(0, 0%, 0%, 0.6)
              );
            ">
                  <div class="bottom-0 d-flex align-items-end h-100 p-4 text-white">
                    <div>
                      <div class="d-flex flex-row small">
                        <p class="text-uppercase">
                          <a href="#!" class="text-reset">Sport</a>
                        </p>
                        <p class="mx-2">•</p>
                        <p>06/25/2022</p>
                      </div>
                      <h5 class="fw-bold pb-1">Grand Prix Cycliste de Montréal.</h5>
                      <p class="small mb-0">
                        By <a href="#!" class="text-reset">Amanda Queens</a>
                      </p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-6 col-lg-7 col-xl-8 mb-4">
            <div class="bg-image rounded-6">
              <img class="w-100" src="https://mdbootstrap.com/img/new/blog/40.jpg"
                style="object-fit: cover; height: 421px" alt="Alternative text" />
              <a href="#!">
                <div class="mask" style="
              background: linear-gradient(
                to bottom,
                hsla(0, 0%, 0%, 0),
                hsla(0, 0%, 0%, 0.6)
              );
            ">
                  <div class="bottom-0 d-flex align-items-end h-100 p-4 text-white">
                    <div>
                      <div class="d-flex flex-row small">
                        <p class="text-uppercase">
                          <a href="#!" class="text-reset">Travel</a>
                        </p>
                        <p class="mx-2">•</p>
                        <p>06/24/2022</p>
                      </div>
                      <h5 class="fw-bold pb-1">
                        Info: current difficulties for airline passengers.
                      </h5>
                      <p class="small mb-0">
                        By <a href="#!" class="text-reset">Alice Mayer</a>
                      </p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>
        </div>
      </section>
      <!--Section: Design Block-->

    </div>
    <relatedposts />
    <Posts />
  </div>
</template>

<script>
  import relatedposts from '~/components/RelatedPosts'
  import Posts from '~/components/Posts'

  export default {
    components: {
      relatedposts,
      Posts
    },
    name: 'IndexPage'
  }

</script>
