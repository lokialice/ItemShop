<template>
<div>
    <app-header></app-header>
    <app-store></app-store>
    <app-page-back></app-page-back>
</div>
</template>

<script>
import HeaderComp from "@/components/Common/HeaderComponent"
import StoreComp from "@/components/Store/StoreComponent"
import PageBackComp from "@/components/PageBackground/PageBackground"
export default {
    name: "Index",
    components: {
        "app-header": HeaderComp,
        "app-store": StoreComp,
        "app-page-back": PageBackComp
    }
}
</script>
