Checked exceptions
	Compiler requires that these be caught or specified

Checked:
- Throwable
	- Exception
		- IOException
			- FileNotFound Exception
		- Midi Unavailable Exception
Two ways to satisfy compiler
- Catch () (Use when you can handle the problem)
- Specify (throw an exception) (Use when someone else should handle)

Documenting exceptions
	It is important that the caller is aware of exceptions thrown and can properly handle checked exceptions
		You can use @throws tag for this

