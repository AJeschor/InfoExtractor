# InfoExtractor

InfoExtractor is a Python package for extracting phone numbers, links, and emails from text. It provides a simple way to extract these entities from a given text string.

## Installation

You can install InfoExtractor using pip:

```bash
pip install InfoExtractor
```

## Usage

Here's how you can use InfoExtractor in your Python code:

```python
from InfoExtractor.extractor import InfoExtractor

# Example text
text = "Sample text with a phone number (123) 456-7890 and an email address example@email.com."

# Create an instance of InfoExtractor
extractor = InfoExtractor()

# Extract phone numbers
phone_numbers = extractor.extract_phone_numbers(text)
print("Phone numbers:", phone_numbers)

# Extract links
links = extractor.extract_links(text)
print("Links:", links)

# Extract emails
emails = extractor.extract_emails(text)
print("Emails:", emails)
```

## Contribute

### Why and How to Contribute to InfoExtractor

InfoExtractor is an open-source Python package designed for extracting phone numbers, links, and emails from text. Contributing to InfoExtractor not only helps improve the functionality and reliability of the package but also fosters a collaborative community of developers. Here's why and how you can contribute:

#### Why Contribute?

- **Report Issues:** If you encounter any issues while using InfoExtractor, such as bugs or unexpected behavior, reporting them is crucial. By doing so, you help maintain the quality of the package and provide valuable feedback to the developers. Additionally, you can use the issue tracker to suggest new features or enhancements.

- **Improve Features:** Contributing code through pull requests allows you to fix existing issues or extend the functionality of InfoExtractor. Whether it's addressing a bug, adding new features, or enhancing existing ones, your contributions can significantly benefit the project and its users.

#### How to Contribute

1. **Setup the Project on Your Local Machine:**

    - **Cloning the Repository:** Begin by creating a folder on your local machine and navigating to it. Then, clone the InfoExtractor repository using one of the following commands:
        ```
        git clone https://github.com/AJeschor/InfoExtractor.git
        ```
        or
        ```
        git clone git@github.com:AJeschor/InfoExtractor.git
        ```
        After cloning, navigate into the InfoExtractor folder.

    - **Setting up the Environment:** Optionally, set up a project environment by creating a virtual environment if one needs to install any dependencies.

2. **General Guidelines for Contribution:**

    - **Reporting an Issue:** When reporting an issue, provide clear and detailed information, including a description of the problem, expected behavior, and relevant code snippets if applicable. This helps developers understand and address the issue effectively.

    - **Pull Request:** If you're submitting a pull request, clearly state its purpose in the description. Whether it's fixing a bug, adding features, or enhancing code quality, clearly communicate the intent of your contribution.

    - **Documentation and Comments:** When pushing code changes, ensure proper documentation through docstrings. Additionally, adding comments to your code helps explain its functionality, making it easier for others to understand and review your contribution.

By adhering to these guidelines and actively contributing to InfoExtractor, you play a vital role in improving the package for both current and future users. Your contributions are greatly appreciated and help drive the success of the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
