Jag ändrade "app_name" i "string.xml" från "Hello" till "Någonting nice!".
Jag lade även till "app_text" i "string.xml" med texten "Detta är också nice!"
och lade sedan inte "app_text" i "activity_main.xml".

```
<resources>
    <string name="app_name">Någonting nice!</string>
    <string name="app_text">Detta är också nice!</string>
</resources>

<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Detta är också nice!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/appBarLayout" />
```

![](screenshot.jpg)