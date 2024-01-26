
# FAQ Compenent
This React application serves as a Frequently Asked Questions (FAQ) component, providing a user-friendly interface to display common questions and answers. The project is structured into three main components: FAQComp, FAQItem, and the main application component App.

## Components
1. FAQComp:
The FAQComp component is responsible for rendering a list of FAQs. It utilizes the FAQItem component for each FAQ entry. The FAQs are defined in an array, and the component maps through them to generate the FAQ items.

2. FAQItem:
The FAQItem component represents an individual FAQ entry. It features a question and answer pair. The visibility of the answer is toggled using the useState and useEffect hooks. The question can be expanded or collapsed by clicking on it.

3. App:
The App component is the main entry point for the application. It renders the FAQComp component and includes a simple heading to introduce the Frequently Asked Questions.
