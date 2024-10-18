
## Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages listed in `requirements.txt`

## Setup

1. Clone the repository:

    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create a virtual environment and activate it:

    ```sh
    python -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

## Running the Notebooks

1. Start Jupyter Notebook:

    ```sh
    jupyter notebook
    ```

2. Open the desired notebook from the Jupyter interface:
    - For BeautifulSoup examples, navigate to the `BeautifulSoup` directory and open `bs_example_X.ipynb`.
    - For Selenium examples, navigate to the `Selenium` directory and open `selenium_example_X.ipynb`.

3. Run the cells in the notebook to execute the code.

## Examples

### BeautifulSoup

- `bs_example_1.ipynb`: Parses a local HTML string and extracts elements using BeautifulSoup.
- `bs_example_2.ipynb`: Fetches a webpage using `requests` and parses it with BeautifulSoup.

### Selenium

- `selenium_example_1.ipynb`: Showing how to run a simple Selenium script.
- `selenium_example_2.ipynb`: How to use Selenium to interact with a webpage and scrape data.
- `selenium_example_3.ipynb`: How to handle a page with infinite scrolling.
- `selenium_example_4.ipynb`: Using Selenium to capture requests and responses.

## License

This project is licensed under the MIT License.