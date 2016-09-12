## Chapter 0

**0-0** 

	\\a small C++ program
	include <iostream>
	int main()
	{
		std::cout << "Hello, world!" << std::endl;
		return 0;
	}


Result:

	Hello, world!

**0-1** *3+4* Adds 3 and 4

**0-2**

	// a small C++ program
	#include <iostream>
	int main()
	{
    	std::cout << "This (\") is a quote, and this (\\) is a backslash." << std::endl;
    	return 0;
	}

Result:   
  
	This (") is a quote, and this (\) is a backslash.  


**0-4**

	// a small C++ program
	#include <iostream>
	int main()
	{
		std::cout <<
		"// a small C++ program\n"
		"#include <iostream>\nint main()\n"
		"{\n"
		"\tstd::cout << \"Hello, world!\" << std::endl;\n"
		"\treturn 0;\n"
		"}" << std::endl;
    return 0;
	}

Result:

	// a small C++ program
	#include <iostream>
	int main()
	{
		std::cout << "Hello, world!" << std::endl;
		return 0;
	}
 
**0-5** It is not a valid program - no scope {} around main.

**0-6** It is a valid program.

**0-7** It is not a valid program as */ ends the comment.

**0-8** It is a valid program as */ ignored

**0-9** Shortest valid program

*Explicitly stating return 0:*

	int main(){return 0;}

*Allowing main() to default to return 0:*

	int main(){}

**0-10**

  
	#include <iostream>
	int 
	main
	(
	) 
	{
	std
	::
	cout 
	<< 
	"Hello, world!" 
	<< 
	std
	::
	endl
	;
	return 
	0
	;
	}

Result:

	Hello, world!

