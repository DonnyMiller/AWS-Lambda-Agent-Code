# AWS-Lambda-Agent-Code

This code is written in Python and is linked to my AWS Connect's Contact Flow. When it gets to a point in the Flow, this Function is called, which in turn calls an API that gets sent the area code of the caller. The API returns the state to my function, and my function returns the state back to the Contact Flow. It is then saved in the Contact information under 'state' in my administrator acccount.
