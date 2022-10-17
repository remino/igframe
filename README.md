igframe
=======

By Rémino Rem <https://remino.net/>

Fit an image into a specific ratio for Instagram.

[Code & Download](https://github.com/remino/igframe/)

- [Getting Started](#getting-started)
	- [Prerequisites](#prerequisites)
	- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)



## Getting Started

### Prerequisites

* [imagemagick](https://imagemagick.org)

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
    ```sh
    git clone https://github.com/github_username/repo_name.git
    ```
3. Install NPM packages
    ```sh
    npm install
    ```
4. Enter your API in `config.js`
    ```js
    const API_KEY = 'ENTER YOUR API';
    ```

[Back to top](#igframe)



## Usage

```
igframe 1.1.1

USAGE: igframe [<options>] <input> [<output>]

Fit an image into a specific ratio for Instagram.

If output name is not specified, the same name than the input will be used,
suffixed by '-out'.

OPTIONS:

	-a        Sharpen resized image.
	-b        Add border, or passe-partout, around picture.
	-B        Do not add border.
	-c        Specify background colour by name or hex value (e.g. #0011aa). Defaults to 'white'.
	-s        Use square ratio (1:1, 1080x1080). (Default.)
	-h        Show this help screen.
	-l        Use landscape ratio (4:3, 1080x810).
	-p        Use portrait ratio (4:5, 1080x1350).
	-t        Use story ratio (9:16, 1080x1920).
	-v        Show version.

```

[Back to top](#igframe)



## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

[Back to top](#igframe)



## License

Distributed under the ISC License. See `LICENSE.txt` for more information.

[Back to top](#igframe)



## Contact

Rémino Rem
https://remino.net/

[Back to top](#igframe)



## Acknowledgments

* []()
* []()
* []()

[Back to top](#igframe)

