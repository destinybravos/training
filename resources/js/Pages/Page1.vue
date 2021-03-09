<template>
    <web-layout>
        <destiny></destiny>
        <silver></silver>
        <nyore></nyore> 
        <ebube></ebube> 
    </web-layout>
</template>

<script>
import WebLayout from "../Layouts/WebLayout";
import Destiny from "../TestComponents/Destiny";
import Silver from "../TestComponents/Silver";
import Nyore from '../TestComponents/Nyore';
import Ebube from '../TestComponents/Ebube';

export default {
    components: { 
        WebLayout, 
        Destiny,
        Silver, 
        Nyore,
        Ebube
    }
}
</script>