<template>
    <div>
        <h3>
            Messages
        </h3>
        <ul v-for="message in messages">
            <li>{{ message }}</li>
        </ul>
    </div>
</template>
<script>
export default {
    data(){
        return {
            messages : ["hello", "hi", "waddup", "nihao"]
        }
    }
}
</script>