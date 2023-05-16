# javadoc-notes
javadoc documentation notes

javadoc notes:

comment:
	###class
	###method
	###parameter (@param)
	###return value (@return)

----------------------------------------

##comments:

/***/

/** The notes. */

----------------------------------------

##class

**Format:**
/** This sentence tells what the class is or does. */

----------------------------------------

##method

summary section:
	displays the first sentence of the comment
	the end of the sentence is marked by a period and whitespace

Detail Section
	displays the entire comment

**FORMAT:**
/** Summary section sentence. Detail section sentence. */

*NOTE on Whitespace*
/** This sentence is the main method. */
(above shows sentence summary of method section, followed by a "." then a space " ")

/** This sentence is the main method. This sentence is the detail section.*/
(the second sentence following the ". " space and period, is the "method detail section")


-------------------------------------------
##parameter (@param)

A parameter is a local variable that's used inside of a method 

parameters are declared in method headers

@param
	this describes a parameter
	must appear after: 
		a summary description, 
		a detail description, 
		or another @param tag

###written as follows:
@param parameterName Description

  *parameterName* is: the name of the parameter 

  *Description* is:  the comment itself 

**FORMAT:**
/** Summary description sentence is the main method. 
Detail description of method.
@param parameterName Description of parameter.
*/

-------------------------------------------------

##return value (@return)

this describes a return value, the value being returned by a method 

the @return tag must be placed *after* a summary description, a detail description, or another @return tag

###written as follows:

@return Description

**FORMAT:**
/** Summary description sentence is the main method. 
Detail description of method.
@param parameterName Description of parameter.
@return Description of return value.
*/





