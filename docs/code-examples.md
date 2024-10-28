``` py title="add_numbers.py"
# Function to add two numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result = add_two_numbers(5, 3)
print('The sum is:', result)
```

``` JSON title="Set Locale" linenums="1"
{
	"Locales": [
		{	
			"LangCode": "de",
			"Active": true,
            "Name": "Deutsch",
            "DefaultCode": "DE",
            "Subcategories": [
				{
                	"Code": "DE",
	                "Active": true,
    	            "Name": "Deutschland"
				}
			]
		},
		{
            "LangCode": "en",
            "Active": true,
            "Name": "English",
            "DefaultCode": "SA",
            "Subcategories": [
                {
                "Code": "GB",
                "Active": true,
                "Name": "United Kingdom"
                },
                {
                "Code": "US",
                "Active": true,
                "Name": "United States"
                }
			]
		}
	]
}
```