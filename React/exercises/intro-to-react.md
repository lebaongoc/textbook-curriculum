# Intro to React

Complete this worksheet with your seat squad. Some items are questions, some items are exercises to extend your hello world React application.

## Test your Knowledge

1. What is the purpose of `create-react-app`?

1. How do you start up your development server for your React application?

1. Why is the following react render function invalid?
    ```JavaScript
    render() {
        return (
          <header>
            <h1>Hello Neat Header</h1>
          </header>
          <p>
            Welcome to my React application!
          </p>
        );
      }
    ```

1. Which of the two JSX code options should you choose? **Why?**

    a.
    ```javascript
    <header class='main-header'>
    </header>
    ```
    b.
    ```javascript
    <header className='main-header'>
    </header>
    ```

1. Add another `img` tag to your `render` function to an image of your choice. The image source should be an absolute URL from an image already uploaded on the internet.

1. What is wrong with this test?

  ```javascript
    // src/App.js
    import React from 'react';
    import ReactDOM from 'react-dom';
    import { mount, shallow } from 'enzyme';
    import App from './App';

    describe('<App />', () => {

      test('will match the last snapshot with deep rendering', () => {
        const wrapper = mount(<App />);
        expect(wrapper).toMatchSnapshot();
      });
    });
  ```

1. Explain the difference between shallow and deep rendering and give an example of when you would use each.

1. **Challenge**: Create a local variable in your `render` function equal to your name. Update the `render` function to display the value associated with this local variable.
