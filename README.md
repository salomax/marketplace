# [openMarketplace](https://salomax-marketplace.appspot.com) 

[![Join the chat at https://gitter.im/salomax/openMarketplace](https://badges.gitter.im/salomax/openMarketplace.svg)](https://gitter.im/salomax/openMarketplace?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
<sup>open source light ERP for e-commerces</sup>

![Build](https://travis-ci.org/salomax/openMarketplace.svg)
![Code Climate](https://codeclimate.com/github/salomax/openMarketplace/badges/gpa.svg)
![Test Coverage](https://codeclimate.com/github/salomax/openMarketplace/badges/coverage.svg)

### Enviroment

- Google Appengine (Endpoints API) and Datastore
- Python
- Bootstrap and JQuery

### Modules in development
- Products
- Suppliers
- Purchases
- Sales
- Cash Flow
- Dashboard
- Reports

### To Do Features
- Android and iOS clients

### Git

	git add .
	git commit -m "Comments"
	git push

### Dev server

	$ dev_appserver.py . --log_level=debug [--clear_datastore] [--clear_search_indexes]

### Upload Application (Example)

	$ appcfg.py -A salomax-marketplace update .

### WebClient

	https://your-app-id.appspot.com/

### Endpoints API

	http://your-app-id.appspot.com/_ah/api/explorer
	
## License

See [LICENSE](https://github.com/salomax/openMarketplace/blob/master/LICENSE).	

