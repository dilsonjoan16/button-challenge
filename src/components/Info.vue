<template>
  <div class="Info">
    <img alt="Vue logo" src="../assets/logo.png" class="my-5" />
    <div class="container mt-5">
      <div class="col-12 text-align-center">
        <!-- Button trigger modal -->
        <button
          type="button"
          class="btn btn-outline-dark"
          data-toggle="modal"
          data-target="#staticBackdrop"
        >
          Launch static backdrop modal
        </button>

        <!-- Modal -->
        <div
          class="modal fade"
          id="staticBackdrop"
          data-backdrop="static"
          data-keyboard="false"
          tabindex="-1"
          aria-labelledby="staticBackdropLabel"
          aria-hidden="true"
        >
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="staticBackdropLabel">
                  ButtonsChallenges
                </h5>
                <button
                  type="button"
                  class="close"
                  data-dismiss="modal"
                  aria-label="Close"
                >
                  <span aria-hidden="true">&times;</span>
                </button>
              </div>
              <div class="modal-body">
                Reto de los Botones, la finalidad de este reto es mejorar el
                uso y conocer la mayoria de elementos que componen a este
                componente sumamente importante en cualquier desarrollo web.
              </div>
              <div class="modal-footer">
                <button
                  type="button"
                  class="btn btn-secondary"
                  data-dismiss="modal"
                >
                  Close
                </button>
                <router-link to="/about">
                  <button
                    type="button"
                    class="btn btn-primary"
                    data-dismiss="modal"
                  >
                    Understood
                  </button>
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="my-4 mx-auto">
        <h1>
            <i>Buttons Challenges</i>
        </h1>
        <p>
            <strong>
                Reto de los Botones, la finalidad de este reto es mejorar el
                uso y conocer la mayoria de elementos que componen a este
                componente sumamente importante en cualquier desarrollo web.
            </strong>
        </p>
    </div>
  </div>
</template>
<script>
export default {
  name: "Info",
};
</script>
<style scoped>
.Info {
  background-color: slategray;
  height: 50vh;
}
</style>
