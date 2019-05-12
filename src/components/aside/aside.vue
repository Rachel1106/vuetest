<template>
    <div class="aside">
       <el-container>
            <el-aside width="200px" style="background-color: rgb(238, 241, 246)">
                <el-menu :default-openeds="['2']">
                    <el-submenu index="1">
                        <template slot="title"><i class="el-icon-message"></i>首页</template>
                    </el-submenu>
                    <el-submenu index="2">
                        <template slot="title"><i class="el-icon-service"></i>用户信息</template>
                        <el-menu-item index="1-1">用户列表</el-menu-item>
                        <el-menu-item index="1-2">用户信息</el-menu-item>
                    </el-submenu>
                    <el-submenu index="3">
                        <template slot="title"><i class="el-icon-goods"></i>商品信息</template>
                        <el-menu-item index="1-1">商品列表</el-menu-item>
                        <el-menu-item index="1-2">商品信息</el-menu-item>
                    </el-submenu>
                     <el-submenu index="4">
                        <template slot="title"><i class="el-icon-printer"></i>图表</template>
                        <el-menu-item index="1-1">折线图</el-menu-item>
                        <el-menu-item index="1-2">饼状图</el-menu-item>
                    </el-submenu>
                </el-menu>
            </el-aside>
       </el-container>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .el-aside {
        color: #333;
    }
</style>

