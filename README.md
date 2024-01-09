## Ruby Hello World

<a name="readme-top"></a>
<div align="center">
    <img src="logo-julio.png" alt="main-logo" width="500"  height="auto" />
  <br/>
  <h3><b>Ruby Hello World</b></h3>
</div>
# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [📖 Ruby Hello World ](#-ruby-hello-world-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Database](#database)
    - [Usage](#usage)
    - [Run tests](#run-tests)
    - [Deployment](#deployment)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [❓ FAQ ](#-faq-)
  - [📝 License ](#-license-)

# 📖 Ruby Hello World <a name="about-project"></a>

This project was created to practice setting up a Ruby on Rails project with PostgreSQL as the database, the creation and implementation of views, controllers, migrations, adding documentation, and using GitFlow. In addition, it also plan to provide foundational knowledge about the folder and file structure of Ruby on Rails. All of these elements are essential pieces of knowledge for becoming a great Ruby on Rails developer. Later on, I will be working on more complex and robust projects, but as they say, first things first.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails 7.1.2</a></li>
  </ul>

### Key Features <a name="key-features"></a>

- **Hello world view.**
- **PostgreSQL as database.**


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

[Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)

### Setup

```sh
cd my-folder
git clone https://github.com/Alejandroq12/hello-rails.git
```

### Install

This project does not require additional dependencies, just Ruby interpreter. However, it uses RuboCop as a linter and you should set it up as well.

```sh
bundle install
```

### Database

Before running the migrations and seeds, ensure that PostgreSQL is installed and running:

```sh
sudo service postgresql start
```

Run migrations:

```sh
rake db:migrate
```

Add the seeds(omit it for this project):

```sh
rake db:seed
```

### Usage

To run the project, navigate to the project directory and execute the following command:

```sh
rails server
```

### Run tests

To run tests, run the following command:

This feature is under construction!
```sh
# rubocop
```

### Deployment

You can deploy this project using:

Not available at the moment.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Authors <a name="authors"></a>

👤 **Julio Quezada**

- GitHub: [Alejandroq12](https://github.com/Alejandroq12)
- Twitter: [@JulioAle54](https://twitter.com/JulioAle54)
- LinkedIn: [Julio Quezada](https://www.linkedin.com/in/quezadajulio/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- **Add more views.**
- **Add validations.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project please give a star.
Thanks in advance.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank all of my colleagues who inspire to do my best everyday.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ (optional) -->

## ❓ FAQ <a name="faq"></a>

**What did you learn?**

- I have learned about generating controllers, setting PostgreSQL as the default database, running migrations, understanding the project's file structure, configuring views, working with the project locally, using GitFlow, documenting a project, and adding instructions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>