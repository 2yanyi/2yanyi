### Hey 👋, I'm xzyan

![](https://github.com/xzyan/xzyan/blob/master/assets/header_.png)

```go
profile := `
Thanks for visiting my GitHub profile, it's great to meet you here! 😊

Here are some quick things about me:
`

fmt.Printf("%s\n", profile)

me := map[string]string{
	"Name":    "Yan yingsong",
	"Job":     "Software Engineer",
	"Company": "DBAPPSecurity IC",
}

for k, v := range me {
	fmt.Printf("- %s: %s \n", k, v)
}
```
