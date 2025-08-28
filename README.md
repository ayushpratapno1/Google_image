# Google Image Generator

A Python-based project that generates images using Google Image Search. This repository provides an automated way to generate and retrieve images based on given keywords, useful for creative projects, machine learning datasets, or personal use.

## Features

- Generate images for any keyword or phrase using Google Image Search.
- Supports generating multiple images instantly.
- Optionally outputs image URLs and metadata including image size and source.
- Command-line interface for easy usage.
- Compatible with Python 2.x and 3.x.
- Can be extended with Selenium for enhanced capabilities.

## Installation

Clone the repository:

git clone https://github.com/ayushpratapno1/Google_image.git

cd Google_image


Install the required dependencies (update the package list based on your actual dependencies):

pip install -r requirements.txt

For generating larger batches or enhanced functionalities, install Selenium and download geckodriver:

- Install Selenium:

pip install selenium

- Download geckodriver for your OS from [Mozilla’s GitHub releases](https://github.com/mozilla/geckodriver/releases) and add it to your system PATH.

## Usage

Run the main script with your search keyword(s) to generate images:

python google_images_generate.py --keywords "cats" --limit 100

Common options include:

- `--keywords`: Specify search terms.
- `--limit`: Number of images to generate per keyword.
- `--print_urls`: Print URLs of the generated images.
- `--output_directory`: Specify where to save generated images.
- `--metadata`: Save image metadata.

Check available options with:

python google_images_generate.py --help

## How It Works

The script uses web scraping techniques or a Google Image API (based on implementation) to generate image results and retrieve related images programmatically. For larger generation limits, Selenium browser automation is used.

## Use Cases

- Creating image datasets for machine learning.
- Generating images for research and creative projects.
- Automated image generation for demos or testing.

## Contribution

Contributions, bug reports, and feature requests are welcome! Please fork the repo and submit pull requests.
