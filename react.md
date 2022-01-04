
# What is HOC (Higher Order Component)?
* A HOC is a function which takes component as a argument and return new component.
* Main advantage of HOC is reusing components.
* Whereas a component convert props into UI, a HOC transforms a component into another component. 
* Please check a small Example below
```
function logProps(WrappedComponent) {
  return class extends React.Component {
    componentDidUpdate(prevProps) {
      console.log('Current props: ', this.props);
      console.log('Previous props: ', prevProps);
    }
    render() {
      // Wraps the input component in a container, without mutating it. Good!
      return <WrappedComponent {...this.props} />;
    }
  }
}
```

