<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { margin: 0; background: #000; color: white; font-family: sans-serif; overflow: hidden; }
        .app { width: 100vw; height: 100vh; display: flex; align-items: center; justify-content: center; position: relative; }
        video { width: 100%; height: 100%; object-fit: cover; }
        .sidebar { position: absolute; right: 15px; bottom: 100px; display: flex; flex-direction: column; gap: 20px; text-align: center; }
        .btn { background: none; border: none; color: white; font-size: 30px; }
    </style>
</head>
<body>
    <div class="app">
        <video id="v" loop autoplay muted src="https://www.w3schools.com/html/mov_bbb.mp4"></video>
        <div class="sidebar">
            <button class="btn" onclick="alert('Calling...')"><i class="fas fa-video"></i></button>
            <button class="btn" style="color:red"><i class="fas fa-heart"></i></button>
            <div style="font-size:12px">1.2M</div>
            <button class="btn"><i class="fas fa-comment"></i></button>
            <div style="font-size:12px">500</div>
        </div>
    </div>
</body>
</html>
