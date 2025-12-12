## Django Template

### Python version compatibility

This project currently depends on `rembg==2.0.30`, which supports Python 3.10 but not Python 3.11 or newer. The Poetry configuration therefore pins the allowed interpreter range to `>=3.10,<3.11`.

If you install dependencies with Python 3.11+ (for example, 3.12.7), Poetry will fail with a message similar to `Current Python version (3.12.7) is not allowed by the project (>=3.10,<3.11)`. To avoid the error, use Python 3.10.x when setting up the environment.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/GB6Eki?referralCode=U5zXSw)
