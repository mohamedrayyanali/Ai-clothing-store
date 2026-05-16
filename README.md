# Ai-clothing-store
The AI Virtual Try-On Smart Mirror is an intelligent retail technology system that allows users to virtually wear clothes digitally without physically trying them on.  Using AI-powered body scanning, computer vision, and clothing simulation, the system captures the user’s body measurements and overlays selected outfits onto the user in real time.  

# AI Virtual Try-On Smart Mirror

An AI-powered smart mirror and virtual clothing try-on system built using Raspberry Pi 5, stereo vision cameras, computer vision, and AI-based body measurement technology.

# Overview

The AI Virtual Try-On Smart Mirror is a smart retail technology project that allows users to virtually try clothes without physically wearing them.

The system captures the user’s full body using a stereo camera, calculates body measurements using AI and computer vision, and overlays uploaded clothing designs onto the user in real time.

This project combines hardware and software to create a futuristic virtual fitting experience for:

Fashion stores
Shopping malls
E-commerce platforms
Clothing brands
Smart retail systems
Digital fashion technology
Main Features
Real-time body scanning
AI pose detection
Body measurement extraction
Virtual clothing fitting
Smart mirror display
Clothing mockup upload system
Live virtual preview
Stereo depth vision support
Raspberry Pi based edge AI system
Modular and portable setup
Project Workflow
Camera Capture
      ↓
AI Pose Detection
      ↓
Body Measurement Extraction
      ↓
Clothing Selection
      ↓
Virtual Cloth Mapping
      ↓
Real-Time Try-On Preview
System Architecture
Hardware Components
Main Processing Unit
Raspberry Pi 5 (8GB Recommended)
Active Cooling Fan
128GB MicroSD / SSD
Official Power Adapter
Camera System
Waveshare IMX219-83 Stereo Camera
Dual 8MP Binocular Camera
Depth Vision Support
Display System
TV / Monitor / Smart Mirror
HDMI Output Display
Optional Touch Support
Lighting
White LED Light Strips
Soft Lighting for Better Detection
Structural Components
3D Printed Camera Mount
Aluminum/Wooden Frame
Cable Management Setup
# Why Raspberry Pi 5?

The Raspberry Pi 5 acts as the main brain of the system.

It handles:

AI processing
Camera input
Image processing
Body measurement calculations
Clothing overlay rendering
Display output
Local data storage

The Raspberry Pi 5 was selected because of:

Better CPU performance
Better camera support
HDMI display support
Low power consumption
Compact size
Portability
Cost effectiveness
Why Stereo Camera?

A stereo camera is required because the project needs depth understanding and body shape estimation.

Unlike normal webcams, stereo cameras use two lenses to calculate:

Depth
Distance
Body proportions
Shoulder width
Body structure

This improves:

Body measurement accuracy
Clothing alignment
Virtual fitting realism
Background separation
Software Stack
Backend
Python

# Main programming language for AI and computer vision.

Flask / FastAPI

Used for backend APIs and communication.

AI & Computer Vision
OpenCV

Used for:

Image processing
Camera handling
Object detection
Cloth mapping
MediaPipe

Used for:

Pose estimation
Body landmark detection
Skeleton tracking
TensorFlow / PyTorch

Used for:

AI model support
Future AI improvements
Advanced fitting systems
Frontend
React

Used for:

User dashboard
Clothing selection UI
Real-time preview interface
Database
SQLite / MongoDB

Stores:

Clothing assets
User measurements
Captured images
Settings
Body Detection Workflow

The stereo camera captures the user from two viewpoints.

The AI system processes the frames and detects body landmarks such as:

Head
Shoulders
Chest
Waist
Arms
Legs
Knees
Ankles

Using depth calculations and AI pose detection, the system estimates body measurements.

These measurements are then used to align clothing onto the user.

Virtual Clothing Overlay System

# The virtual try-on system works by:

Uploading clothing mockups
Detecting body landmarks
Resizing clothing assets
Aligning clothes to the body
Rendering a live preview

# The software dynamically adjusts clothing position based on:

User pose
Body size
Shoulder width
Arm position
Body proportions
Camera Mount Design

# A custom 3D printed clip-on camera mount was designed for:

TVs
Monitors
Laptops

# Features:

Rounded rectangular stereo camera enclosure
Adjustable clip mechanism
Lightweight design
Easy installation
Stable positioning

The mount can be attached to the top edge of displays.

# blueprint and photos
<img width="1536" height="1024" alt="realworldlook" src="https://github.com/user-attachments/assets/104f1a14-db5c-4ce9-9380-2a5e49adcc97" />
<img width="1402" height="1122" alt="blueprint" src="https://github.com/user-attachments/assets/c3de3ea4-102c-44f6-9d53-1104394c50db" />
