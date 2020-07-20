# Bitcoin-api--flask

https://jsonlint.com/

Create a web app using Flask framework:

It will get the Bitcoin price for the user.
Use API with JSON response for getting the price.
Suggested API: CoinDesk (https://www.coindesk.com/)
Display your result in a styled web page.
Plus (Optional) : Try to deploy your app on a cloud server if possible. [Heroku/Netlify]
Due Date: 23 July, 2020


response:


{
	'time': {
		'updated': 'Jul 19, 2020 11:25:00 UTC',
		'updatedISO': '2020-07-19T11:25:00+00:00',
		'updateduk': 'Jul 19, 2020 at 12:25 BST'
	},
	'disclaimer': 'This data was produced from the CoinDesk Bitcoin Price Index (USD). Non-USD currency data converted using hourly conversion rate from openexchangerates.org',
	'chartName': 'Bitcoin',
	'bpi': {
		'USD': {
			'code': 'USD',
			'symbol': '&#36;',
			'rate': '9,135.9760',
			'description': 'United States Dollar',
			'rate_float': 9135.976
		},
		'GBP': {
			'code': 'GBP',
			'symbol': '&pound;',
			'rate': '7,270.2818',
			'description': 'British Pound Sterling',
			'rate_float': 7270.2818
		},
		'EUR': {
			'code': 'EUR',
			'symbol': '&euro;',
			'rate': '7,993.3303',
			'description': 'Euro',
			'rate_float': 7993.3303
		}
	}
}
