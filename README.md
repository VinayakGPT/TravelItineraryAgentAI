# Itinerary Planning Agent

This project implements an **Itinerary Planning Agent** designed to assist users in creating optimized travel plans based on their preferences and constraints. The agent leverages advanced AI capabilities to suggest itineraries tailored to specific requirements.

---

## Features

- Interactive user interface for itinerary planning.
- AI-based optimization to suggest travel plans.
- Customizable input for user preferences such as destinations, time, and budget.
- Dynamic adjustments based on user feedback.

---

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   cd itinerary_planning_agent
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Create a `.env` file to store your API keys and environment variables:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   ```

---

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook itinerary_planning_agent.ipynb
   ```

2. Run the notebook cells sequentially to initialize and execute the agent.

3. Input your travel preferences as prompted, and the agent will generate an optimized itinerary.

---

## Dependencies

This project requires the following Python libraries:

- `langchain`
- `python-dotenv`
- `openai`
- `IPython`
- Additional dependencies as listed in `requirements.txt`.

---

## API Keys

To use this project, you need a valid OpenAI API key. Add it to your `.env` file or set it as an environment variable:
```bash
export OPENAI_API_KEY=your_openai_api_key
```

---

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit your changes.
4. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- The project utilizes OpenAI's GPT models for itinerary optimization.
- Special thanks to the open-source community for supporting development.

