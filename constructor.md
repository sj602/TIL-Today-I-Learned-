React constuctor 쓰임

1. Is it necessary to call super() inside constructor?
    - Calling super() is necessary only if you need to have a constructor.
	- if there is a constructor in your code, then you MUST call super.

2. What is the difference between callling super() and super(props)?
	- Call super(props) only if you want to access this.props inside the constructor. React automatically set it for you if you want to access it anywhere else.
