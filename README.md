# PasswordViewDemo
Sample Demo explaining PasswordView Component recently added in Google Design Guidelines  [here](https://www.google.com/design/spec/components/text-fields.html#text-fields-password-input).

# Screenshot

<img src="https://github.com/BhaveshPatadiya/PasswordViewDemo/blob/master/screenshot.png"  width="400px" />

# HOW TO USE :

    <com.bhavesh.passwordview.PasswordView
                android:id="@+id/password"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:hint="@string/password_hint"
                app:useStrikeThrough="true" />


# Gradle Dependency :

    compile 'com.bhavesh.passwordview:password-view:1.0.0'

# Coming soon to a jcenter near you ...

*in the meantime you can use maven
          { 
              url 'https://dl.bintray.com/bhaveshpatadiya/maven' 
          }
in your top-level build.gradle
