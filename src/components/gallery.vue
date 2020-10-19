<template>
    <div>
<b-row >
<b-col sm="4" v-for="personaje in personajes" :key="personaje.id" >
  <b-card
    :title="personaje.nombre"
    :img-src="personaje.imagen"
    img-alt="Image"
    img-top
    style="max-width: 20rem;"
    class="mb-2"
  >
  </b-card>
  </b-col>
  </b-row>
</div>
</template>

<script>
export default {
    name: 'gallery',
    // props: {},
    data: function(){
        return {

                personajes: [
                    {
                    'id': 1,
                    'nombre': 'Morty',
                    'imagen': 'https://rickandmortyapi.com/api/character/avatar/2.jpeg'
                    },
                    {
                    'id': 2,
                    'nombre': 'Rick',
                    'imagen': 'https://rickandmortyapi.com/api/character/avatar/1.jpeg'
                    },
                    {
                    'id': 3,
                    'nombre': 'Summer',
                    'imagen': 'https://rickandmortyapi.com/api/character/avatar/3.jpeg'
                    },
                    {
                    'id': 4,
                    'nombre': 'Beth',
                    'imagen': 'https://rickandmortyapi.com/api/character/avatar/4.jpeg'
                    },
                    {
                    'id': 5,
                    'nombre': 'Jerry',
                    'imagen': 'https://rickandmortyapi.com/api/character/avatar/5.jpeg'
                    }
                    ]
            
        }
    },
    // computed: {},
    methods: {
        // -- Metodos
    },
    // components: {},
}
</script>

<style scoped>
div{
display:flex;
justify-content:center;
margin-top:20px;
}
</style>