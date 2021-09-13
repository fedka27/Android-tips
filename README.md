### Disable overriding dark mode for app
1.  In **onCreate()** method in the Activity class, after **super.onCreate(savedInstanceState)** paste this code:
`AppCompatDelegate.setDefaultNightMode(AppCompatDelegate.MODE_NIGHT_NO)`
3. Add to the theme app in **styles.xml** paste:
`<item name="android:forceDarkAllowed" tools:targetApi="29">false</item>`

