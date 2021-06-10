<template>
    <div class="container">
        <div class=""></div>
    </div>
</template>
<script>
import axios from "axios";
export default {
    name: "AppMovies",
    methods: {
        getMovies() {
            let apikey = '1d78f81fda3f2ea4ce4e762cafafda63';
            axios.get(`https://api.themoviedb.org/3/movie/550?api_key=${apikey}`)
            .then(response => console.log(response.data))
            .catch(error => console.log(error));
        }
    }
}
</script>