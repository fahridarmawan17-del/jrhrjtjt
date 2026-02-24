package com.example.aplikasisaya

import android.os.Bundle
import androidx.appcompat.app.AppCompatActivity
import android.widget.TextView

class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)

        val textView = TextView(this)
        textView.text = "Hello Farid!"
        textView.textSize = 24f

        setContentView(textView)
    }
}# jrhrjtjt
