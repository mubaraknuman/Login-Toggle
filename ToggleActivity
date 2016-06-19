package com.numan.user.login_screen;

import android.content.Context;
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.widget.CompoundButton;
import android.widget.Switch;
import android.widget.Toast;

public class Toggle extends AppCompatActivity {


    Context context = this;
    CharSequence text = "Checked In";
    CharSequence text2 = "Checked Out";
    public int duration = Toast.LENGTH_SHORT;
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_toggle);
        Switch toggle = (Switch) findViewById(R.id.switch1);
        assert toggle != null;
        toggle.setOnCheckedChangeListener(new CompoundButton.OnCheckedChangeListener() {
            public void onCheckedChanged(CompoundButton buttonView, boolean isChecked) {
                if (isChecked) {
                    //Open Check In Activity
                    Toast toast = Toast.makeText(context, text, duration);
                    toast.show();

                } else {
                    // The toggle is disabled
                    Toast toast = Toast.makeText(context, text2, duration);
                    toast.show();
                }
            }
        });
    }
}
