# Regular-Expression-for-Email
Regular expression for email using java spring boot

### Email Validation regexp :-

<b><i>regexp = "^(.+)@(.+)$"</b></i>

### For example in java spring boot.


`@NotEmpty(message = "Email field should not be empty")
    @Email(regexp = "^(.+)@(.+)$", message = "Invalid email pattern")
    private String email;`
