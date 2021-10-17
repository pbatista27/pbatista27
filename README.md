### I speak to computers too 👋

<!--
**pbatista27/pbatista27** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

import "fmt"

// I is about me
type I struct {
	am       string
	love     []string
	workWith []string
	aspire   string
}

func main() {
	me := I{
		am:       "Naren Yellavula",
		love:     []string{"Software", "Books", "Travel"},
		workWith: []string{"Python 3", "JavaScript ES6", "React", "Go", "AWS"},
		aspire:   "To make this world a better and safe place with technology",
	}
	fmt.Println(me)
}


