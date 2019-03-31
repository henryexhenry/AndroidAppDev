# Mobile Computing project

- Environment
    - react native 0.59
    - expo 32.0.0
    - react: 16.5.0
    - react-navigation: ^3.0.9

- Workflow
    - Download expo client
        - npm install -g expo-cli
    - Create a project using expo
        - ```expo init <project name>```
        - ```cd <project name>```
        - ```npm start``` OR ```expo start```
    - Testing on android device
        - connect device and computer by usb
        - using the same WIFI
        - In Metro Bundler , switch connection to Local
        - In Metro Bundler , click 'Run on Android device/emulator'

- RN useful concepts
    - Props
    - PropTypes / defaultProps
        - To specify the type of attributes in an element(or tag)(or class)
        - eg.
        ```
        static propTypes = {
            name:PropTypes.string,
            age:PropTypes.number
        }
        ```
        - {array, bool, func, number, object, string, func.isRequires, any.isRequired}
    - state
        - setState()
    