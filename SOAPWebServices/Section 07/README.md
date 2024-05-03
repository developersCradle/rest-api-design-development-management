# SOAP Web Services 07 - Writing a Web service Client: Stub generation

```
public List<String> getProductCategories() {
		
		List<String> categories = new ArrayList<>();
		
		categories.add("Books");
		categories.add("Music");
		categories.add("Movies");
		categories.add("Cartoon");
		
		return categories;
	}
```

- Converting this to SOAP Web Service.