# Ran-San-Moi
<!DOCTYPE html>
<html>
<head>
	<title>HieuQuag09</title>
	<style>
		canvas {
			border: 1px solid #000;
		}
	</style>
</head>
<body>
	<canvas id="canvas" width="400" height="400"></canvas>
	<script>
        window.onload = function() {
          
          // Thiết lập canvas và ngữ cảnh
          var canvas = document.getElementById("canvas");
          var ctx = canvas.getContext("2d");
          
          // Thiết lập mặc định cho game
          var size = 10;
          var food = {x: 0, y: 0};
          var snake = [{x: 200, y: 200}];
          var direction = "right";
          var score = 0;
          
          // Thêm sự kiện phím vào hướng
          document.addEventListener("keydown", function(e) {
            if (e.keyCode == 37 && direction != "right") {
              direction = "left";
            } else if (e.keyCode == 38 && direction != "down") {
              direction = "up";
            } else if (e.keyCode == 39 && direction != "left") {
              direction = "right";
            } else if (e.keyCode == 40 && direction != "up") {
              direction = "down";
            }
          });
          
          // Tạo hàm vẽ rắn
          function drawSnake() {
            for (var i = 0; i < snake.length; i++) {
              ctx.fillStyle = "#000";
              ctx.fillRect(snake[i].x, snake[i].y, size, size);
            }
          }
          
          // Tạo hàm vẽ mồi
          function drawFood() {
            ctx.fillStyle = "#f00";
            ctx.fillRect(food.x, food.y, size, size);
          }
          
          // Tạo hàm kiểm tra va chạm
          function checkCollision() {
            if (snake[0].x < 0 || snake[0].x >= canvas.width) {
              return true;
            } else if (snake[0].y < 0 || snake[0].y >= canvas.height) {
              return true;
            }
            
            for (var i = 1; i < snake.length; i++) {
              if (snake[0].x == snake[i].x && snake[0].y == snake[i].y) {
                return true;
              }
            }
            
            return false;
          }
          
          // Tạo hàm tạo mồi mới
          function createNewFood() {
            food.x = Math.floor(Math.random() * (canvas.width - size) / size) * size;
            food.y = Math.floor(Math.random() * (canvas.height - size) / size) * size;
          }
          
          // Tạo hàm cập nhật trạng thái của rắn
          function updateSnake() {
            // Di chuyển rắn
            var head = {x: snake[0].x, y: snake[0].y};
            if (direction == "left") {
              head.x -= size;
            } else if (direction == "up") {
              head.y -= size;
            } else if (direction == "right") {
              head.x += size;
            } else if (direction == "down") {
              head.y += size;
            }
            snake.unshift(head);
            
            // Kiểm tra va chạm
            if (checkCollision()) {
              clearInterval(intervalId);
              alert("Game over!");
            }
            
            // Kiểm tra nếu rắn ăn được mồi
            if (snake[0].x == food.x && snake[0].y == food.y) {
              score++;
              createNewFood();
            } else {
              snake.pop();
            }
          }
          
          // Tạo hàm vẽ điểm
          function drawScore() {
            ctx.fillStyle = "#000";
            ctx.font = "16px Arial";
            ctx.fillText("Score: " + score, 10, 20);
          }
          
          // Vòng lặp chính
          var intervalId = setInterval(function() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            updateSnake();
            drawSnake();
            drawFood();
            drawScore();
          }, 100);
        }
	</script>
</body>
</html>
