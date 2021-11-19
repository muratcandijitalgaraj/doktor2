<template>
  <div class="home">
    <h3>Doktor Listesi</h3>
    <b-container class="bv-example-row">
      <b-row>
        <b-col
          ><div>
            <b-card
              title="Prof. Dr. Lorem Ipsum"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem"
              class="mb-2, doctorCard"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>
              <div class="doctorLinks">
                <p class="ücret">Ücret: 250 TL</p>
                <router-link to="/özgeçmiş">Özgeçmiş</router-link>
              </div>

              <router-link to="/randevuAl">Randevu al</router-link>
            </b-card>
          </div></b-col
        >
        <b-col
          ><div>
            <b-card
              title="Prof. Dr. Lorem Ipsum"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem"
              class="mb-2, doctorCard"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>
              <div class="doctorLinks">
                <p class="ücret">Ücret: 250 TL</p>
                <router-link to="/özgeçmiş">Özgeçmiş</router-link>
              </div>

              <router-link to="/randevuAl">Randevu al</router-link>
            </b-card>
          </div></b-col
        >
        <b-col
          ><div>
            <b-card
              title="Prof. Dr. Lorem Ipsum"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem"
              class="mb-2, doctorCard"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>
              <div class="doctorLinks">
                <p class="ücret">Ücret: 250 TL</p>
                <router-link to="/özgeçmiş">Özgeçmiş</router-link>
              </div>

              <router-link to="/randevuAl">Randevu al</router-link>
            </b-card>
          </div></b-col
        >
      </b-row> </b-container
    ><b-container class="bv-example-row">
      <b-row>
        <b-col
          ><div>
            <b-card
              title="Prof. Dr. Lorem Ipsum"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem"
              class="mb-2, doctorCard"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>
              <div class="doctorLinks">
                <p class="ücret">Ücret: 250 TL</p>
                <router-link to="/özgeçmiş">Özgeçmiş</router-link>
              </div>

              <router-link to="/randevuAl">Randevu al</router-link>
            </b-card>
          </div></b-col
        >
        <b-col
          ><div>
            <b-card
              title="Prof. Dr. Lorem Ipsum"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem"
              class="mb-2, doctorCard"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>
              <div class="doctorLinks">
                <p class="ücret">Ücret: 250 TL</p>
                <router-link to="/özgeçmiş">Özgeçmiş</router-link>
              </div>

              <router-link to="/randevuAl">Randevu al</router-link>
            </b-card>
          </div></b-col
        >
        <b-col
          ><div>
            <b-card
              title="Prof. Dr. Lorem Ipsum"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem"
              class="mb-2, doctorCard"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>
              <div class="doctorLinks">
                <p class="ücret">Ücret: 250 TL</p>
                <router-link to="/özgeçmiş">Özgeçmiş</router-link>
              </div>

              <!-- <b-button href="#" variant="primary"> -->
              <router-link to="/randevuAl">Randevu al</router-link>
              <!-- </b-button> -->
            </b-card>
          </div></b-col
        >
      </b-row>
    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
<style scoped>
.doctorLinks {
  display: flex;
  justify-content: space-around;
}
.doctorCard {
  box-shadow: 10px 10px 5px grey;
  margin: 2em;
}
/* .doctorCard:hover{
} */
.ücret {
  color: green;
}
</style>
