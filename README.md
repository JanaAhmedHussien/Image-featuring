﻿# Image Featuring & Labeling

## Description
This project demonstrates how to perform image scraping, processing, and analysis using Python. It includes querying Google Images via SERP API for sprite sheets of cartoon faces, saving images locally, cropping sub-images, and applying facial detection with landmarks.

---

## Features
1. **Google Images Search with SERP API**:
   - Search for "face sprite sheet" using the SERP API.
   - Retrieve image results in a structured format.

2. **Image URL Extraction**:
   - Extract URLs from the `images_results` and fetch the `original` image URLs.

3. **Image Saving**:
   - Request and save images locally for further processing.

4. **Image Cropping**:
   - Crop sub-images from a sprite sheet and save them as individual images.

5. **Facial Detection**:
   - Detect faces in images using a face detection algorithm.

6. **Facial Landmark Detection**:
   - Identify facial landmarks (e.g., eyes, nose, mouth) on detected faces.

---

## Prerequisites
- **Python** (version 3.8+)
- Required Libraries:
  - `serpapi` (for Google Image search)
  - `requests` (for fetching images)
  - `matplotlib` (for displaying images)


Install dependencies:
```bash
pip install serpapi requests
