webcam-mocap/
├── main.py                  # Entry point
├── capture/
│   ├── body.py              # MediaPipe Pose
│   ├── hands.py             # MediaPipe Hands
│   └── face.py              # MediaPipe Face Mesh
├── exporters/
│   ├── json_exporter.py     # Export to .json
│   └── bvh_exporter.py      # Export to .bvh (Blender-ready)
├── visualizer.py            # Skeleton overlay on webcam feed
├── recorder.py              # Start/stop recording session
└── README.md
