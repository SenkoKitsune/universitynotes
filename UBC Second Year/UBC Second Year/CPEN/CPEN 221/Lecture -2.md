Rice's Theorem
	All non-trivial, semantic properties of programs are undecidable
		A semantic property is one about the program's behaviour (for instance, does the program terminate for all inputs), unlike a syntactic property (for instance, does the program contain if-elseif-else statements)
Specifications answer the question
	Specification says:
		1) What does a particular function/procedure does, in a ambiguous way
	Preconditions (requires)
		Conditions on state that must be true for the implementation to work
		Assumptions made by the implementer
		If not true, then implementation behaviour is undefined
	Postconditions (effects)
		What the implementer of the method promises to do
		Often what the method returns
	Frame condition (modifies)
		Identifies which objects may be modified
		Often omitted: meaning nothing is modified

Javadoc Specifications
	Preconditions @param
	Postconditions @return
	Frame conditions (include in @param)
We can also add our own tags to Javadoc