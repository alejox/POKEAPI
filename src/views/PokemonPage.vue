<template>
  <h1>¿Quién es este Pokémon?</h1>
  <PokemonPicture :pokemonId="412" :showPokemon="true" />
  <PokemonOptions />
</template>

<script setup>
import PokemonOptions from '@/components/PokemonOptions.vue';
import PokemonPicture from '@/components/PokemonPicture.vue';

import getPokemonOptions from '@/helpers/getPokemonOptions';

console.log(getPokemonOptions());
</script>
