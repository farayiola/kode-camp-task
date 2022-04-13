package com.example.mine

import android.annotation.SuppressLint
import androidx.appcompat.app.AppCompatActivity
import android.os.Bundle
import android.widget.Button
import android.widget.TextView
import android.widget.Toast

class MainActivity : AppCompatActivity() {

    @SuppressLint("SetTextI18n")
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)

        val tap: Button = findViewById(R.id.button)
        val textResult: TextView = findViewById(R.id.bio)
        tap.setOnClickListener {
            val toast = Toast.makeText(this, "Hardworking", Toast.LENGTH_SHORT)
            toast.show()
            textResult.text = "hardworking, lazy, somewhat lazy, very lazy, and dedicated"
        }

    }
}
