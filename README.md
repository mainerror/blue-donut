<h1 align="center">Blue Donut</h1>

<div align="center">
  <strong><i>Tools to help Legacy Coalition members live in their space.</i></strong>
  <br>
  <br>

  <a href="https://github.com/Aimsucks/blue-donut/">
    <img src="https://img.shields.io/pypi/pyversions/Django?style=for-the-badge" alt="Python Versions" />
  </a>

  <a href="https://github.com/Aimsucks/blue-donut/issues">
    <img src="https://img.shields.io/github/issues/aimsucks/blue_donut?style=for-the-badge" alt="PyPi" />
  </a>

  <a href="https://discordapp.com/invite/UCK8ase">
    <img src="https://img.shields.io/discord/645977792265322506?color=%237289DA&label=DISCORD&style=for-the-badge" alt="Discord" />
  </a>

  <a href="https://github.com/Aimsucks/blue-donut/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/aimsucks/blue-donut?style=for-the-badge" alt="Discord" />
  </a>
</div>

<br>

<div align="center">
  This is a website that hosts a multitude of features. Currently the only supported feature (and on this repo) is a built-in route planner that is still being actively developed.
  The route planner currently only supports manual input. Automatic updates are being actively worked on.
</div>

## Installation

Configure everything in the `local.py` file in `blue_donut`.

Install Poetry and then install the requirements.

```commandline
poetry install
npm i
```

Make the bundle, run migrations, and populate the database.

```commandline
npm run dev

poetry run python manage.py migrate
poetry run python manage.py download_sde
```

Finally, run the server.
```commandline
poetry run python manage.py runserver
```

## License

This project is licensed under MIT.

## Contributing

Feel free to contribute to this project, a helping hand is always appreciated.
If you have any feature suggestions, don't hesitate to make an issue.

[Join our discord server](https://discordapp.com/invite/UCK8ase).
