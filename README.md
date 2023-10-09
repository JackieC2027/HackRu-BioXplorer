# HackRu-BioXplorer
BioXplorer is an interactive web application designed to provide users with an immersive experience in the world of animals. Whether you are a nature enthusiast or a beginner in the field of animal exploration, BioXplorer offers a range of features to enhance your learning journey. The application allows users to identify animals from images, explore animal locations on a map, learn about animal evolution, and even contact experts for more information. As a result of time constraints, this project was completed in 24 hours, in relation to Rutger's University annual Hackathon, where we were recognized as the winners of the "Education" track.

Click on the thumbnail for our demonstration!

[<img src="https://i.postimg.cc/MGQ29Z7N/gallery.jpg" width="50%">](https://www.youtube.com/watch?v=bIrPtQfJUgA)

## Home
The home page of BioXplorer provides users with an introduction to the application's key features. It includes:
- Interactive Introduction: Learn about the purpose of BioXplorer and its mission to provide an enriching experience in the world of animals.
- Features Overview: Discover the main functionalities of the application, including the Learning Chatbot, GPT Animal Detection, Contribution Opportunities, and Map API.

![Screenshot](https://i.postimg.cc/MGQ29Z7N/gallery-1.jpg)

## Animal Identification and Learning Chatbot
The Upload page allows users to upload images of animals and learn more about them. Here's how it works:
- Image Upload: Users can upload animal images, which are then processed using a pre-trained VGG16 model for animal identification.
- Animal Information: If the animal is successfully identified, the application provides information about the animal, including its common name and interesting facts.
- Interactive Learning: Users can ask questions about the identified animal, and the application's Learning Chatbot provides specific and concise answers, enhancing the user's knowledge about the animal.

[![gallery-1.jpg](https://i.postimg.cc/445CLScf/gallery-1.jpg)](https://postimg.cc/8sjnsww9)

## Animal Locations on Map
The Map page enables users to explore animal locations on a map. Here's what you can do:
- Location Submission: Users can submit animal locations by entering an address. The application uses geocoding to pinpoint the location on the map.
- Interactive Mapping: Animal locations submitted by users are displayed on the map, providing a visual representation of animal sightings in different areas.

[![gallery-2.jpg](https://i.postimg.cc/prkgmmvh/gallery-2.jpg)](https://postimg.cc/YLGXVqhM)

## Animal Evolution Information
The Evolution page allows users to explore the evolutionary history of animals. Here's how it works:
- Animal Selection: Users can choose a specific animal from a dropdown menu.
- Milestone Selection: Users can select a milestone in history (e.g., 15 million years ago) to learn about the evolution of the chosen animal during that period.
- Interactive Learning: The application generates concise and informative bullet points about the animal's evolution during the selected timeframe.

[![gallery-3.jpg](https://i.postimg.cc/x89wjKwV/gallery-3.jpg)](https://postimg.cc/7GQsmTPK)

## Contact Us
The Contact page enables users to get in touch with the BioXplorer team. Here's what you can do:
- User Information: Users can provide their name and email address for communication purposes.
- Message Submission: Users can type their messages or inquiries in a text area and submit them to the BioXplorer team.
- Helpful Links: The page includes links to external resources related to animal welfare and conservation for users seeking additional information.

[![gallery-4.jpg](https://i.postimg.cc/Jn3wWTdQ/gallery-4.jpg)](https://postimg.cc/N90C6xty)

## Running

To run the BioXplorer web application, make sure you have Streamlit installed. If you haven't installed Streamlit yet, you can do so using the following command:
```
pip install streamlit
```
Once you have Streamlit installed, navigate to the directory where your main.py file is located using the command line or terminal. Then, execute the following command to start the Streamlit application:
```
streamlit run main.py
```
This command will launch the BioXplorer web application locally, allowing you to explore its features in your web browser. Enjoy exploring the world of animals with BioXplorer!
