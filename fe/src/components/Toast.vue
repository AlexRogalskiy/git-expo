<template lang="html">
    <div class="toast">
        {{ toast.message }}
        {{ toast.button }}
    </div>
</template>

<script>
export default {
    props: ['toast']
}
</script>

<style lang="less">
.toast {
    position: absolute;
    display: inline-block;
    left: 5%;
    bottom: 5%;
    z-index: 9999 !important;
    background: #000;
    opacity: 0.9;
    border-radius: 2px;
    margin: auto;
    box-shadow: 0 0 3px #000;
    text-shadow: none;
    color: #DDD;
    text-align: left;
    padding: 10px 20px;
    letter-spacing: -0.3px;
    font-size: 15px;
}

.toast-button {
    display: inline-block;
    margin-left: 10px;
    font-weight: bold;
    color: #2196F3;
    font-size: 16px;
}

</style>
