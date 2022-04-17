#include "main.h"
/**
 * invalidInputs - test user inputs
 * @p: input string
 * Return: true or false
 */
_Bool invalidInputs(const char *p)
{
	/* NULL */
	if (!p)
		return (false);
	/* "%" */
	if (*p == '%' && !*(p + 1))
		return (false);
	/* "% " */
	if (*p == '%' && *(p + 1) == ' ' && !*(p + 2))
		return (false);
	return (true);
}
