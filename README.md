
# Blog Generator 🤖

This Streamlit application generates blog content based on user-provided inputs. It utilizes the LLama 2 language model to create engaging blog posts quickly and efficiently.

## Features

- Generate blog content on various topics for different job profiles.
- Customize the length of the generated blog post.
- Choose from predefined job profiles like Researchers, Data Scientists, and Common People.
- Simple and intuitive user interface powered by Streamlit.

## How to Use

1. **Installation**: Ensure you have Python installed on your machine. Clone this repository and install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. **Run the App**: Execute the following command in your terminal to run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

3. **Input**: Enter the topic for your blog post in the provided text input field.

4. **Additional Inputs**: Specify the desired word count for the blog post and select the job profile you are writing the blog for.

5. **Generate**: Click the "Generate" button to generate the blog post.

6. **View Output**: The generated blog post will be displayed on the app interface.

## Example Usage

Here's how you can use the application to generate a blog post:

1. Input: "Machine Learning in Healthcare"
2. Word Count: 500
3. Job Profile: Data Scientist
4. Click "Generate"
5. View the generated blog post on the app interface.

## Dependencies

- Streamlit
- Langchain (for prompts and LLama 2 model)

