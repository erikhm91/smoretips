<template>
    <section>
        <div>
            <p><bold>Når</bold> skal jeg gå?</p>
            <p><a>{{ dateOfTrip }}</a> kl. <a>{{ hourOfTrip }}</a></p>
        </div>

        <div>
            <p><bold>Hvor</bold> skal jeg gå?</p>
            <p><a>{{ locationText }}</a></p>
        </div>

    </section>
</template>

<script>
export default {
    // setup() {
        
    // },
    props: {
        dateOfTrip: String,
        hourOfTrip: Number,
        locationText: String,
        freshTracks: Boolean
    }
}
</script>

<style scoped>

</style>