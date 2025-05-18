
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  
</head>
<body>

  <h1>Cub3D</h1>
  <p><strong>Author:</strong> Your Name</p>
  <p><strong>School:</strong> 42</p>
  <h2>🖼️ Screenshots</h2>

<img src="cub.png" alt="Cub3D Screenshot 1" style="max-width:100%; border-radius:8px; margin-bottom: 1rem;" />

<img src="sc.png" alt="Cub3D Screenshot 2" style="max-width:100%; border-radius:8px;" />

  <h2>📌 Description</h2>
  <p>
    <strong>Cub3D</strong> is a simple 3D game engine developed as a project at 42 School.
    The goal is to render a 3D environment using raycasting techniques similar to early 90s FPS games like <em>Wolfenstein 3D</em>.
  </p>

  <h2>🚀 Features</h2>
  <ul>
    <li>Raycasting rendering system</li>
    <li>Basic movement and rotation</li>
    <li>Mini-map</li>
    <li>Textured walls and sprites</li>
    <li>Floor and ceiling coloring</li>
    <li>Configurable via .cub map files</li>
  </ul>

  <h2>🛠️ Installation</h2>
  <pre><code>git clone https://github.com/yourusername/cub3d.git
cd cub3d
make</code></pre>

  <h2>🎮 Usage</h2>
  <pre><code>./cub3D maps/map.cub</code></pre>
  <p>Controls:</p>
  <ul>
    <li><code>W / A / S / D</code>: Move forward, left, back, right</li>
    <li><code>Left / Right Arrow</code>: Rotate view</li>
    <li><code>ESC</code>: Exit the game</li>
  </ul>

  <h2>📁 Map File Format (.cub)</h2>
  <p>The map file must follow a strict structure, including texture paths and the map layout.</p>
  <pre><code>NO ./textures/wall_north.xpm
SO ./textures/wall_south.xpm
WE ./textures/wall_west.xpm
EA ./textures/wall_east.xpm
F 220,100,0
C 225,30,0

1111111111
1000000001
1011000001
1000000001
1111111111</code></pre>

  <h2>✅ Requirements</h2>
  <ul>
    <li>Linux system</li>
    <li>gcc and make</li>
    <li>mlx (MiniLibX) - included or installed separately</li>
  </ul>

  <h2>📚 Resources</h2>
  <ul>
    <li><a href="https://harm-smits.github.io/42docs/projects/cub3d" target="_blank">42 Docs: Cub3D</a></li>
    <li><a href="https://github.com/qst0/ft_libgfx" target="_blank">MiniLibX Repository (Linux)</a></li>
  </ul>

  <h2>🧠 Credits</h2>
  <p>This project was made as part of the 42 cursus. Big thanks to peers, tutors, and the 42 community!</p>

</body>
</html>
