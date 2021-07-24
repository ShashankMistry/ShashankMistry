<div style="display:flex;">
<img alt="App image" src="GIF/name1.gif" width="100%">
</div>

```java
        
import com.developer.shashank;

public class GitHubActivity extends AppCompatActivity implements shashank.OnReadMeListener {

        protected void onCreate(Bundle savedInstanceState) {
                String name = "Shashank Mistry";
                String title = "Android Developer";
                String location = "Anand, Gujarat";

                skills();
          }

          private void skills() {
                String[] languages = {"C","JAVA","PYTHON","HTML","CSS"};
                String[] databases = {"MySQL","SQlite","NoSQL"};
                String[] tools = {"Android Studio","VSCode","Jupyter"};
          }

           @override
           public void onReadMeListener(R -> {
               Toast.makeText(GitHubActivity.this,"Thanks for visiting my github",Toast.LENGTH_LONG)
               .show();
           }
        }
```

<img href="https://shashankmistry30.medium.com/" src="https://img.icons8.com/color/50/000000/medium-logo.png"  width="20%"/>

