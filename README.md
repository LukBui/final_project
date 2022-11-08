This is final project of CodeAcademy course!

## Installation

#### Create virtual environment in project's root directory:

```Shell
python -m venv venv
```

#### Activate the virtual environment:

- ##### For Linux / Mac:

  ```Shell
  source venv/bin/activate
  ```

- ##### For Windows:
  ```Shell
  source venv/Scripts/activate
  ```

#### Install the required packages:

```Shell
pip install -r requirements.txt
```

### Running

##### Run the development server:
```Shell
flask run
```
##### Alternative without setting environment variables:
```Shell
flask --app app --debug run
```