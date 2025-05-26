 //geting  the button using findviewbyid for the start button that takes you to a new activity
        val button = findViewById<Button>(R.id.button)
        button.setOnClickListener {
            val intent = Intent(this,
                MainActivity2::class.java)
            startActivity(intent)
        }
        } 
        the two parralel arrays declared and initialised on the second activity
        val Question = arrayOf(
       "the sky is blue."
       "water is h2o."
       "i am ur dad."
       "food is solid."
       "life is hard."


    )
        //score declared and initialised to zero
        var score = 0

    val Answer = arrayOf(
        true
        true
        false
        true
        true
    )
the two buttons for false and true 
     val trueButton = findViewById<Button>(R.id.truebutton)
        val falseButton = findViewById<Button>(R.id.falseButton)

        trueButton.setOnClickListener { check(true) }
        falseButton.setOnClickListener{ check(false) }
