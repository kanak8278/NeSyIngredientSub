# Multimodal Neurosymbolic Knowledge Web for Ingredient Substitution

A system for personalized ingredient substitution using deep learning and contextual knowledge. Query via text, structure, or images with dietary constraints. Provides relevant substitutes with reasoning for informed dietary choices.

**Note:** This work is currently under review at AAAI. The demo and dataset will be made available upon acceptance and the conclusion of the review process.

## Features

- **Multimodal Queries**: Supports natural language, structured, and image-based queries.
- **Dietary Constraints**: Allows filtering based on 21 dietary labels (e.g., vegan, vegetarian, lactose-free).
- **Contextual Knowledge**: Integrates data from Edamam, ConceptNet, FlavorDB, and Wikidata.
- **Reasoning**: Provides explanations for the substitutions based on trusted sources.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/MultimodalIngredientSubstitution.git
    cd MultimodalIngredientSubstitution
    ```

2. Create a virtual environment and activate it:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Run the application**:
    ```sh
    python app.py
    ```

2. **Access the UI**:
   Open your browser and navigate to `http://localhost:5000`.

3. **Query the system**:
   - **Structured Query**: Enter the ingredient name, constraints, and number of substitutes.
   - **Natural Language Query**: Type your query in natural language (e.g., "Find vegan substitutes for chicken").
   - **Image-Based Query**: Upload an image of the ingredient and specify constraints.

## Data Sources

- **Edamam**: Nutrition and dietary labels.
- **ConceptNet**: Ingredient categories and alternative names.
- **FlavorDB**: Flavor compounds associated with ingredients.
- **Wikidata**: Information on origin, usage, and dietary restrictions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- AAAI for the submission template.
- Datasets and APIs: Edamam, ConceptNet, FlavorDB, Wikidata.
