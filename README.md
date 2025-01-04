# YouTube Video Analysis System

## Project Overview

A comprehensive system has been developed to analyze YouTube videos through multiple modalities including visual content, audio transcription, and metadata extraction. The system leverages state-of-the-art AI models to process and index video content for efficient searching and analysis.

## Demo

https://github.com/user-attachments/assets/eba2f7a8-6813-481f-a04e-33d99263ce49

## Key Features Implemented

### Design

![image](https://github.com/user-attachments/assets/e70a9b3d-9b5f-4afa-b6e1-03a5beba5166)

### Video Processing

- Frame extraction at configurable intervals using OpenCV
- Efficient batch processing of video frames
- Automatic video downloading and cleanup
- Video metadata extraction including title and ID

### Visual Analysis

- Integration of OpenAI's CLIP model for visual understanding
- Vector embeddings generation for each extracted frame
- Similarity-based image search functionality
- Efficient batch processing of frames for CLIP analysis

### Audio Processing

- Audio extraction and transcription using Whisper AI
- Subtitle extraction and formatting
- Support for both manual and auto-generated subtitles
- Multi-language support with focus on English

### Data Storage

- Vector storage implementation for frame embeddings
- PostgreSQL integration for vector similarity search
- Efficient batch document addition
- Metadata storage for frame timestamps and numbers

### Optimization Features

- Batch processing for improved performance
- GPU acceleration when available
- Efficient memory management
- Automatic resource cleanup

### Search Capabilities

- Image-based frame search using CLIP embeddings
- Cosine similarity-based matching
- Configurable similarity thresholds
- Fast retrieval of relevant frames

## Technical Stack

- Computer Vision: OpenCV, PIL
- AI Models: CLIP (Visual), Whisper (Audio)
- Vector Storage: Custom implementation with PostgreSQL
- Video Processing: yt-dlp
- Deep Learning: PyTorch
- Data Processing: NumPy

## Future Improvements

The system can be enhanced with:

- Real-time video processing capabilities
- Advanced caching mechanisms
- Multi-GPU support for faster processing
- Extended metadata extraction
- Enhanced search functionality
- User interface development
