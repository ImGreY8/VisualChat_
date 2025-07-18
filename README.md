## USER INTERFACE
![image](https://github.com/user-attachments/assets/616272d3-1728-4ec2-96b6-48a128d16e1c) 
## UPLOAD IMAGE
![WhatsApp Image 2025-07-07 at 10 15 40 PM](https://github.com/user-attachments/assets/efd866d0-3d1a-450f-a591-b7a9cc8e18c3) 
## GENERATED CAPTIONS
![image](https://github.com/user-attachments/assets/a797dce7-9dc0-41ac-ace9-d16608fcfed2)
## GENERATED SIMILAR IMAGES
![doggo2](https://github.com/user-attachments/assets/b8c214d3-f6d5-44d6-8ff4-f780177f32e0)


## 🧠 Key Features:
- Image Upload or Camera Input: Users can upload an image from local storage or capture it directly using a webcam.
- Automatic Image Captioning: Uses the BLIP model (Bootstrapped Language-Image Pretraining) from Hugging Face Transformers to describe the content of an image in natural language.
- Voice Assistance (Text-to-Speech): Reads out captions and guides users during the interaction to support visually impaired individuals using pyttsx3.
- Image Similarity Search: Uses the generated caption as a semantic query to retrieve 2–3 visually similar images using the Unsplash API.
- Real-time Processing: Includes webcam input to allow real-time image capture and processing.
- Accessible UI: Built using Streamlit for an easy-to-use web interface with buttons for all interactions.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔄 Workflow:
- Image Input: Upload an image or capture one using the webcam.
- Caption Generation: Process the image using BLIP to generate a short caption.
- Voice Output: Speak the caption aloud using pyttsx3.
- Similar Image Retrieval: Use the caption as a query to fetch images from Unsplash.
- Display: Show retrieved similar images in a visual layout.
