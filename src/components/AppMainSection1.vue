<script>
export default {
  name: 'AppMainSection1',
}
</script>

<template>
    <div class="ContainerSection">
        <div class="ContainerContent">
            Content Goes Here!
        </div>
    </div>
</template>

<style lang="scss" scoped>
.ContainerSection{
    height: 150px;
    width: 100%;
    display: flex;
    align-items: center;
    background-color: #1c1c1c;
    & .ContainerContent{
        color: white;
        width: 50%;
        text-align: center;
        font-size: 2em;
        font-weight: bold;
    };
};
</style>