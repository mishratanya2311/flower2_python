# Flower2 Python

A Python-based 3D botanical animation project that procedurally creates a cinematic Sakura (Japanese cherry blossom) blooming sequence.

## Project Structure

```text
flower2_python/
├── generate_sakura_animation.py
├── sakura_3d_botanical_animation.mp4
└── README.md
```

## About the Project

This project uses Python to generate a stylized, detailed 3D-inspired animation of a Sakura flower as it develops from a branch and buds into a full bloom.

## Animation Stages

1. **Branch Growth** – the branch begins to grow.
2. **Bud Formation** – flower buds appear.
3. **Petal Unfolding** – the petals gradually open.
4. **Full Bloom** – the flower reaches its completed form, with stamens and leaves.
5. **Cinematic Reveal** – drifting petals, bokeh, and camera movement complete the scene.

## Technologies Used

- Python
- NumPy
- OpenCV
- FFmpeg

## Files

- `generate_sakura_animation.py` – Python script used to generate the animation.
- `sakura_3d_botanical_animation.mp4` – rendered animation video.

## Requirements

- Python 3
- NumPy
- OpenCV (`opencv-python`)
- FFmpeg installed and available on your system PATH

Install the Python packages:

```bash
pip install numpy opencv-python
```

## How to Run

Open a terminal in the project folder:

```bash
cd flower2_python
```

Run the animation script:

```bash
python generate_sakura_animation.py
```

The rendered video is saved as:

```text
sakura_3d_botanical_animation.mp4
```

To render preview keyframes instead of the full video:

```bash
python generate_sakura_animation.py --preview
```

## Video Specifications

- Resolution: 1080 × 1920
- Frame rate: 30 FPS
- Duration: 18 seconds
- Total frames: 540

## Author

Created by **Tanya**.
