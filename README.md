# Let workaround with a basic CNN example.
In this example, we will package a CNN Appl.

My_app
├── cnn_app
│   ├── __init__.py  # make the folder a package
│   ├── app.py       # contains the Flask app object
│   ├── config.py
│   ├── models.py    # data management
│   └── templates/
└── tests
    ├── conftest.py  # Test cfg 
    └── test_app.py  # unit tests  (Not needed in this example)
