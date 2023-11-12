# Accessible Form Design: Error Indication

When designing accessible forms in mobile applications, it's important to provide clear and specific error messages. The example demonstrates two approaches to error feedback for a form input where a user is required to enter their email address and password.

## Do

- Add icons (✓) / (⨉) to indicate successful/unsuccessful input validation.
- Highlight the input field with an error in red to draw attention.
- Provide a text-based error message below the input field, such as "Incorrect password," to clearly communicate the nature of the error.
- Provide haptic feedback in case of error.

## Don't

- Just changing the border color of the input field to red without any text-based error message can be ambiguous and not accessible to those who have color vision deficiencies.
- Lack of a clear error icon or text can leave users uncertain about what the error is or how to resolve it.