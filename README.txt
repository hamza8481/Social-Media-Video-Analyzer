AI Product Video Generator

Overview
This workflow automates the creation and publishing of short-form promotional videos for new Shopify products. When a new product is added to a Shopify store, the workflow uses AI to analyze the product image, generates an 8-second vertical video, and cross-posts the video to TikTok, Instagram Reels, and YouTube Shorts.

Business Value
1. Hands-free social media marketing for e-commerce stores.
2. High-quality video generation directly from static product photos.
3. Automated logging of successful posts and failure notifications.

Execution Flow
1. Shopify Trigger: Listens for new product creation events.
2. Filter: Ensures the product is active and has an image. Prevents duplicate processing.
3. AI Analysis: An AI model reads the product image to generate a detailed video rendering prompt and a concise caption/selling point.
4. Video Generation: The prompt is sent to an AI video generator to create an 8-second vertical clip.
5. Social Publishing: The generated video and caption are uploaded to configured social media platforms (TikTok, Instagram, YouTube).
6. Logging: Successes and failures are logged to a Google Sheet. If a failure occurs, an email alert is sent via Gmail.
