<template>
    <div>
        <router-link to="/contact"  replace :class="{nav_active: !isActive}" class="nav-tab-item" >
            <span class="nav-icon  icon-uniE919"></span>
            <span class="nav-tab-label">通讯录</span>
        </router-link>
    </div>
</template>

<script>
    export default {
        name: "navcont",
        props:{
            path:String
        },
        computed:{
            isActive(){
                return this.$route.path.indexOf(this.path)
            }
        }
    }
</script>

<style scoped>

</style>