<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
<form>
	<div class="username">
		<label>姓名</label>
		<input type="text" name="username" value="xwu">姓名
	</div>
	<div class="password">
		<label>密码</label>
		<input type="password" name="password">密码
	</div>
	<div class="sex">
		<label>性别</label>
		<input type="radio" name="sex" value="男">男
		<input type="radio" name="sex" value="女">女	
	</div> 

	<div class="hobby">
		<label>爱好</label>
		<input type="checkbox" name="hobby" value="sleep">睡觉
		<input type="checkbox" name="hobby" value="sing">唱歌
		<input type="checkbox" name="hobby" value="dance">跳舞	
	</div>

	<div class="city">
		<select name="city">
			<option value="beijing">北京</option>
			<option value="shanghai">上海</option>
			<option value="guangzhou">广州</option>
		</select>
	</div>
	<div class="submit">
		<button>提交</button>
	</div>	
</form>

</body>
</html>
