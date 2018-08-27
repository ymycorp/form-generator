<template>

    <div class="columns is-centered">
        <div class="column is-three-quarters">
            <vue-form-ss class="box animated fadeIn"
                :route-params="[$route.name, null, false]"/>
        </div>
    </div>

</template>

<script>

import VueFormSs from './VueFormSs.vue';

export default {
    components: { VueFormSs },
};

</script>
