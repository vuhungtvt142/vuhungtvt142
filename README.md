### Hi there 👋
### 💬 Ask me about ...
 My name Duong Vu Hung. I am a Machine Vision Engineer. \
 I grdua
<!--
**vuhungtvt142/vuhungtvt142** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

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
		"- ⚡ Quick bio:":                    "A kind of metalHead-synthWave-cyberPunk-melomaniac-gearAddict-amateurMusician-traveler-foodLover-gamer-coder-programmer-catLover-sportsAficionado-gymRat hybrid",
		"- 🔭 I’m currently working on":      "Mercado Libre as a Senior Software Engineer",
		"- 🌱 I’m currently learning":        "Golang, RabbitMQ, Terraform, K8s, DevOps technologies",
		"- 👯 I’m looking to collaborate on": "Python, Golang and Dev/DevOps related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning",
		"- 💬 Ask me about":                  "Python, GO, PHP, Laravel, SQL, Software Design & Architecture, Web-Dev",
		"- 📫 How to reach me:":              "https://github.com/AnhellO#you-can-reach-me-at-alien",
	}
}
