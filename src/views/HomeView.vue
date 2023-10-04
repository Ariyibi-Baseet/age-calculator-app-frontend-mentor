<template>
  <div class="container">
    <div
      class="app-calculator-wrapper d-flex align-items-center justify-content-center"
    >
      <div class="row">
        <div class="col-sm-6 mx-sm-auto">
          <div class="age-calculator-block">
            <!-- Date column area -->
            <div class="date-column">
              <div class="row">
                <div class="col">
                  <label>Day</label>
                  <input
                    type="text"
                    class="form-control mt-2 shadow-none"
                    placeholder="DD"
                    maxlength="2"
                  />
                </div>
                <div class="col">
                  <label>Month</label>
                  <input
                    type="text"
                    class="form-control mt-2 shadow-none"
                    placeholder="MM"
                    maxlength="2"
                  />
                </div>
                <div class="col">
                  <label>Year</label>
                  <input
                    type="text"
                    class="form-control mt-2 shadow-none"
                    placeholder="YYYY"
                    maxlength="4"
                  />
                </div>
              </div>
            </div>

            <div class="line-and-arrow">
              <div class="arrow-wrapper">
                <ArrowIcon />
              </div>
            </div>

            <div class="date-output">
              <div class="years">
                <p><span class="figure">-- </span>years</p>
              </div>
              <div class="months">
                <p><span class="figure">-- </span>months</p>
              </div>
              <div class="days">
                <p><span class="figure">-- </span>days</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ArrowIcon from "@/components/ArrowIcon.vue";
export default {
  name: "HomeView",
  components: {
    ArrowIcon,
  },
};
</script>
