# Translator Application

## Introduction

The Translator Application is developed using React.js. Below is an overview of the key logic and development steps:

1. **Component Structure**: The application consists of two main components - `Translator` and `App`. 
   - `Translator` component handles the translation logic, user inputs, and API requests.
   - `App` component serves as the main container for the `Translator` component.

2. **State Management**: React's `useState` hook is used for managing state within the components.
   - State variables such as `fromText`, `toText`, `fromLanguage`, `toLanguage`, `languages`, and `loading` are declared using the `useState` hook.
   - These state variables manage user inputs, selected languages, translated text, and loading status.

3. **API Integration**: The application integrates with the MyMemory Translation API for translating text.
   - The `handleTranslate` function constructs the API URL with the source text and language pair.
   - Fetch API is used to make a GET request to the API endpoint.
   - Upon receiving the response, the translated text is updated in the state.

4. **User Interaction**:
   - Users can input text in the "Enter Text" textarea.
   - They can select source and target languages from dropdown menus.
   - Clicking the "Translate Text" button triggers the translation process.
   - Translated text is displayed in the designated textarea.
   - Users can listen to the translated text by clicking the volume icon.
   - Copy functionality allows users to copy the translated text to the clipboard.
   - The exchange icon swaps the source and target languages.

## Technology Used

- **React.js**: Frontend JavaScript library for building user interfaces.
- **JavaScript**: Programming language for implementing logic and functionality.
- **HTML/CSS**: Markup and styling languages for structuring and styling the user interface.
- **MyMemory Translation API**: External API used for translating text between languages.

## Screenshots
<img width="960" alt="Screenshot 2024-03-25 125538" src="https://github.com/asish-sutar/React-Translator-App/assets/114928367/435f5f90-eab1-4c8b-9c08-424ae74b5f71">
<img width="960" alt="Screenshot 2024-03-25 125648" src="https://github.com/asish-sutar/React-Translator-App/assets/114928367/6a3b68c8-168a-4e26-a60d-b3d34c04a685">
<img width="956" alt="Screenshot 2024-03-25 125756" src="https://github.com/asish-sutar/React-Translator-App/assets/114928367/3ed75c03-320b-4785-8b92-917665860198">


## Conclusion

The Translator Application is a simple yet effective tool for translating text between different languages. It leverages React.js to provide a responsive and intuitive user experience. With its clean interface and efficient logic, users can easily translate text and perform language conversions.

---
