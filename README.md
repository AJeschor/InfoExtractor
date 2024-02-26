# InfoExtractor

InfoExtractor is a Python package for extracting phone numbers, links, and emails from text. It provides a simple interface to extract these entities from a given text string.

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This README.md file provides installation instructions, usage examples, links to documentation, and information about the license. You can customize it further to include additional details about your package and its features.
