```go
package filipejohansson

type Developer struct {
	Name, Title, Location string
	WorkingOn, Learning   []string
	Skills                map[string][]string
}

var Me = Developer{
	Name:     "Filipe Johansson",
	Title:    "Software Engineer",
	Location: "Porto Alegre, Brazil",

	WorkingOn: []string{
		"Vane — Go-first web framework for WebAssembly",
		"Compiler & developer tooling",
	},

	Learning: []string{
		"Compiler Design", "Framework Architecture", "WebSockets",
	},

	Skills: map[string][]string{
		"Languages": {"Go", "Java", "TypeScript"},
		"Frontend":  {"React", "Angular", "Next.js"},
		"Backend":   {"Go", "Java", "Node.js", "REST APIs", "WebSockets"},
		"Database":  {"PostgreSQL", "MySQL", "MongoDB"},
		"Tools":     {"Git", "Docker", "CI/CD"},
	},
}
```
