<template>
    <h1>Hello, {{world}}!</h1>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';

@Component
export default class App extends Vue {
    private world: string = 'some';
}
</script>