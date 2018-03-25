# password-strength-meter
Ideas, notes, and brainstorms for creating a password strength meter that takes into account human behavior and other heuristics to do a better job of identifying weak passwords.


# Resources

* [Password Strength Indicators Help People Make Ill-Informed Choices](https://www.troyhunt.com/password-strength-indicators-help-people-make-dumb-choices/)
* [Microsoft Identity Protection Team](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/Microsoft_Password_Guidance-1.pdf)
* [UK's NCSC](https://www.ncsc.gov.uk/guidance/password-guidance-simplifying-your-approach)
* [I've Just Launched "Pwned Passwords" V2 With Half a Billion Passwords for Download](https://www.troyhunt.com/ive-just-launched-pwned-passwords-version-2/)
* [Why you can’t trust password strength meters](https://nakedsecurity.sophos.com/2015/03/02/why-you-cant-trust-password-strength-meters/)
* [The Pitfalls of Password Strength Meters](https://www.infosecurity-magazine.com/blogs/password-strength-meters/)
* [The Password Meter](http://www.passwordmeter.com/)
* [From Very Weak to Very Strong: Analyzing Password-Strength Meters](https://www.ndss-symposium.org/ndss2014/programme/very-weak-very-strong-analyzing-password-strength-meters/)
* [CUPS Lab - Password Meter](https://github.com/cupslab/password_meter)

# Ideas
* only warn when a password is **known** to be weak?
* figure out some other way to communicate "as best we can tell, that password isn't garbage. It might still suck though"
* Integrate Pwned Passwords V2 API. It is really fast, so this shouldn't be a problem
* Allow configuration of some other heuristics, such as the name of the service, the user's name, etc. The password can be checked for permutations of all of these
* Need a good UI that doesn't block as all of this stuff is checked. Maybe it is too computationally intensive and should be done on the server side?
