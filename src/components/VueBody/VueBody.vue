<template>
    <div>
        <side-panel></side-panel>
        <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium doloribus voluptatibus, officiis amet quos placeat delectus voluptate exercitationem eveniet cum eligendi sed quam, beatae tempora eos doloremque tenetur sequi quaerat odio repellendus veritatis consequuntur. Placeat eos consequatur est reiciendis, in voluptate ducimus. Molestiae omnis non provident officiis possimus architecto dolorem?</h2>
    </div>
</template>

<script>
import SidePanel from '../../components/VueBody/Subcomponents/SidePanel.vue'

export default {
    name: "VueBody",
    components: {
        SidePanel
    }
}
</script>


<style scoped>
h2{
color: rgb(136, 255, 0);
}
</style>