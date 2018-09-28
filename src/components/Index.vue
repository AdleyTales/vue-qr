<template>
    <div id="adley-index">
        <section class="top">
            <input type="file" id="file_1">
            <br>
            <mt-button type="primary"> 开始上传 </mt-button>
            <span>请上传文件</span>
        </section>
        <section>

        </section>
    </div>
</template>

<script>
export default {};
</script>

<style>
    #adley-index {
        width: 800px;
        height: 200px;
        border: 2px dashed #26a2ff;
        /* background: #eeddee; */
        margin: 0 auto;
        padding: 30px;
        /* box-shadow: 0px 0px 1px #26a2ff; */
    }

    #adley-index #file_1 {
        margin-bottom: 30px;
    }

    #adley-index .top {
        width: 100%;
        height: 100%;
        position: relative;
    }

    #adley-index .top span {
        position: absolute;
        font-size: 80px;
        color: aliceblue;
        top: 50%;
        left: 50%;
        transform: translate(-50% , -50%);
        
    }


</style>
