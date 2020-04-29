# Getting Started
---

<!-- ### Before you begin
1. Create a new [Cloud Platform project](https://console.developers.google.com/projectcreate).
2. [Enable billing](https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project) for your project.

### Creating an API key
1. [Create an API key](https://console.developers.google.com/apis/credentials) in the Google APIs Console.
2. Click **Create credentials**, then select **API key**.
3. Copy the key to the clipboard.
4. Click **Close**.

### Enable the API

Before you can make calls to this API, you need to enable it in the Cloud Platform project you created.
1. [View this API](https://console.developers.google.com/apis/api/{{apiHost}}/overview) in the Google APIs Console.
2. Click the **Enable** button, then wait for it to complete.
3. You can now call the API using the API key you created! -->

### Using the API

 You can use the **Try this API** tool on the right side of the med-opt-stage method page to generate a sample request. An example call to the med-opt-stage method is as following:
 {
	“labs”: {								
		“potassium”: 3.4,
		“creatinine”: 2.3
	},
	“demographics”: {								
		“is_african_american”: false
	},
	“vitals”: {
		“sbp”: 116,
		“hr”: 74
	},
  “medications”:[
   {“name”: “metoprolol_tartrate”, “dose”: 200.0, “unit”: “MG”},
   {“name”: “quinapril”, “dose”: 21.0, “unit”: “MG”},
   {“name”: “sacubitril_valsartan”, “dose”: 100.0, “unit”: “MG”}
	],
 “allergies”:[
	    {“name”: “lisinopril”},
	    {“name”: “spironolactone”}
 ]
}


