<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8" />
	<title></title>
</head>
<body>
	<script type="text/javascript">
		
		var products = ['iphoneX', '小米6', '清风纸巾', '打火机', '电饭锅', '谢谢参与'];

		function getProduct() {

			//生成随机数 Math.random() 0 <= x < 1;
			var random = Math.random();

			if (random >= 0.99) {

				console.log(products[0]);

			} else if (random >= 0.95) {

				console.log(products[1]);

			} else if (random >= 0.8) {

				console.log(products[2]);

			} else if (random >= 0.55) {

				console.log(products[3]);

			} else if (random >= 0.45) {

				console.log(products[4]);

			} else {
				console.log(products[5]);
			}

			

		}

		getProduct();

		// var classRoom = ['学者', '学长', '学生', '学术'];

		// //indexOf: 

		// var isComing = classRoom.indexOf('学长');

		// console.log('isComing ==> ', isComing);

		// if (isComing > -1) {
		// 	console.log('他来了');
		// } else {
		// 	console.log('他逃课了');
		// }
	</script>
</body>
</html>
