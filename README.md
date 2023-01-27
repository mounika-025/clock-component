# Component Life Cycle Phases

Every React Component goes through three phases throughout its lifetime:

1.Mounting Phase
2.Updating Phase
3.Unmounting phase


 # Mounting Phase

In this phase, the instance of a component is created and inserted into the DOM.

Methods:

We mainly use the three methods. The three methods are called in the given order:

1.constructor() =>The constructor() method is used to set up the initial state and class variables.

2.render() => The render() method is used to return the JSX that is displayed in the UI.

3.componentDidMount() => The componentDidMount() method is used to run statements that require that the component is already placed in the DOM.

# Updating Phase

In this phase, the component is updated whenever there is a change in the component's state.

Methods:

1.render()
The render() method is called whenever there is a change in the component's state.

# Unmounting Phase

In this phase, the component instance is removed from the DOM.

Methods:

1.componentWillUnmount()
The componentWillUnmount() method is used to cleanup activities performed.

Example: clearing timers, cancelling API calls, etc.


