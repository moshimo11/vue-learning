/* eslint-disable */
<template>
	<div style="background-color: #FFFFFF;">



      <img src="static/logo.jpg" style="width:600px" class="image"></img>
      <div class="theme">针对当前疫情形势的城市智慧垃圾分类识别系统</div>
		
		  <el-row style="padding: 22px;">
			    <el-col :span="12">

				      <el-card class="box-card":body-style="{ padding: '0px', height: '60%'}">

				        <img src="http://192.168.137.241:5000/video_img_url" class="image" ></img>
				      </el-card>
          </el-col>

			    <el-col :span="8" :offset="2">
			    <img src="static/rubbish.png" class="image"></img>
				      <el-col :offset="5">
				  <el-button type="success" round @click ="takeAPhotho()"></i>拍照</el-button>
			    </el-col>
			    </el-col>
		  </el-row>
		
    <img src="static/step.png" style="width:700px" class="image"></img>
	
	</div>

</template>



<style>
	.image{
		width: 50%;
		height: 60%;
    text-align:center;
	}

  .theme {
    color: #2c3e50;
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 6px;
    text-align:center;
  }

</style>
