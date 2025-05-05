# Props in React: Parent to Child Example

This example defines a `Parent` component that passes a prop called `name` to a `Child` component.

```jsx live
function Child(props) {
  return <p>Hello {props.name}!</p>;
}

function Parent() {
  return (
    <div>
      <h2>This is the parent component.</h2>
      <Child name="Tim" />
    </div>
  );
}

```
