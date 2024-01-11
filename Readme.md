```golang
func main() {
	profile := `
Hi there 👋
great to meet you here! 😊

Here are some quick things about me:
`
	fmt.Println(profile)
	
	me := map[string]string{
		"name":    "Sujay KS",
		"job":     "DevOps/SRE",
		"company": "UniCards",
	}
	for k, v := range me {
		fmt.Printf("- %s: %s \n", k, v)
	}
}
```
