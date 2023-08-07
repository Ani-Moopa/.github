# Moopa

<h2 align="center">About us</h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:": "We are a group of Devs and Designers making this website for fun and learning cause we love to learn  ;)",
		"- 🔭 we're currently working on": "Moopa the ad free anime streaming site and show the world our skills",
		"- 🌱 We're currently using": "We use programming languages such as  JS , and tools like VS code and databases like postgresql ",
		"- 👯 We're looking for -": "anyone who comes here and helps out lmao",
		"- 🤔 Origin country ?":"",
		"- 💬 Ask us about": "Any tech queries or if you have any issue about the project ( open a issue on the repo)  ",
		"- 📫 How to reach us:": "join the discord server(https://discord.gg/v5fjSdKwr2)",
	}
}
```







---
