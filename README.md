# mycode
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>Web作业</title>
		<style type="text/css">
			table tr,td,th{border:1px solid #000;}
			table{border:1px solid #000;}
		</style>
	</head>
	<body>
		<h1>天高科技工作室</h1>
		<h2>Web组</h2>
		<form method="post" action="save.php">
			<label for="name">请输入您的姓名：</label>
			<input type="text" id="name">
			<label for="class">请输入您的班级:</label>
			<input type="text" id="class">
		</form>
		<table>
			 <tbody><!--无需等待表格完全加载完后显示，tbody包含行的内容下载完优先显示-->
			 	<tr>
			 		<th>姓名</th>
			 		<th>组别</th>
			 		<th>学习内容</th>
			 	</tr>
			 	<tr>
			 		<td>XXX</td>
			 		<td>Web组</td>
			 		<td>Web前端入门知识HTML</td>
			 	</tr>
			 	<tr>
			 		<td>XXX</td>
			 		<td>Web组</td>
			 		<td>Web前端入门知识HTML</td>
			 	</tr>
			 </tbody>
		</table>
		    <h3>温馨提示</h3>
	        <ul>
			  <li>工作室有打卡考勤制度,在到达工作室或离开工作室时,请记得打卡</li>
			  <li>平时功课遇到问题时,可以问工作室的师兄师姐</li>
			  <li>工作室有一只可爱的猫,叫聂小倩</li>
			</ul>
			<h3>任务要点</h3>
			<p>第一周是前端和后端集体考核，考核一周后根据你们自己意愿，是选择加入到前端，还是选择加入到后端。</p>
			<p>选择完前后端后，还会有两周的考核时间，如果有意向选择Web前端的同学，请在规定时间提交考核任务。</p>
			<h3>任务谨记</h3>
			<ol>
			   <li>本次考核任务主要是考核大家对HTML标签的理解和使用，在适合场景使用合适的标签</li>
			   <li>考核任务请在4月7号晚上10：00之前提交到邮箱841721534@qq.com</li>
			   <li>在4月7号晚上之前，如果修改过代码，可再次提交任务</li>
			</ol>
			<h3>反馈</h3>
			<form method="post" action="save.php">
			   <textarea ></textarea>
			   <input type="submit" value="提交" name="submitBtn"/>
			</form>
	</body>
</html>

