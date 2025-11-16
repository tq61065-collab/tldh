<!DOCTYPE html>
<html>
<head>
<style>
.box {
  width: 150px;
  height: 150px;

  background-image: url("https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExamhrMGZ5a2Y0cjZydjcyNTg4ZTl4ajZtMGNncHhkNzdyYzg0MXdvMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/42IBrWawqSqwPDk5CF/giphy.gif");
  background-size: cover;      /* ảnh tự động vừa khít */
  background-position: center; /* căn giữa ảnh */

  position: relative;
  animation: zigzag 10s infinite alternate;
}

@keyframes zigzag {
  0%   { left: 0px;   top: 0px; }
  25%  { left: 300px; top: 50px; }
  50%  { left: 0px;   top: 100px; }
  75%  { left: 600px; top: 150px; }
  100% { left: 0px;   top: 200px; }

</style>
</head>
<body>

<div class="box"></div>

</body>
</html>
