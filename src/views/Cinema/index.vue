<template>
    <div id="main">
        <Header title="喵喵影院" />
        <div id="content">
            <CiList />
        </div>
        <TabBar />
    </div>
</template>

<script>
import Header from '@/components/Header';
import TabBar from '@/components/TabBar';
import CiList from '@/components/CiList';

export default {
    name : 'Cinema',
    components : {
        Header,
        TabBar,
        CiList
    }
}
</script>

<style scoped>

</style>
