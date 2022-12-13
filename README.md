# Arithmancer

Arithmancer is a prediction market application. Users can make trades on predictions, betting on how likely an event is to occur. Each prediction is an individual market with a market maker system modeled on Robin Hanson's logarithmic market scoring rules.

This was designed and tested as an internal corporate decision market. Using outside of an organization as a general application will likely require additional features (ex. ACLs, better form validation and security, etc.).

Note: This is not an official Google product.

![Arithmancer](https://storage.googleapis.com/arithmancer-static/arithmancer.png "Preview")


![Arithmancer Prediction](https://storage.googleapis.com/arithmancer-static/arithmancer_prediction.png)
## Getting Started

pip install -r requirements.txt

[Download and install the Google Cloud SDK](https://cloud.google.com/sdk/downloads#interactive), and use dev_appserver.py to run a local server for development. Create your first prediction by going to "/predictions/create". 

### Prerequisites

This runs on App Engine and uses Google Cloud Datastore. Google Cloud SDK is a prerequisite for development and deployment.

## Running the tests

python runner.py app_test.py 

## Contributing

Please read CONTRIBUTING.md for details on contributing.

Features that would be desired/on the roadmap:
- Comments
- ACLs for viewing and trading on a prediction
- Search

## Authors

* **Ben Goldhaber** - *Initial work*
* **Nathan Rogers** - *Daily Price Cron Job*


## License

This project is licensed under the Apache 2 License - see the [LICENSE.md](LICENSE.md) file for details.
