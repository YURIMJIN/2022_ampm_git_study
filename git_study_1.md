# 2022.05.06-07 일정
## 목차
* 자기소개
* 오늘 일정
    - 10시 치과
    - 깃 스터디 과제
    - 모앱 비대면 발표 준비
* 내일 일정
    - 행궁동 놀러 가기

### 자기소개
안녕하세요 저는 소프트웨어공학과 20학번 진유림입니다.

### 오늘 일정
* **10시 치과**
    - 파워체인 교체

* **깃 스터디 과제**
    - VsCode 설치 및 설정
    - markdowm 문법

* **모앱 비대면 발표 준비**<br>
*새로운 액티비티 추가*
```
import android.app.Activity;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;

public class SecondActivity extends Activity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {

        super.onCreate(savedInstanceState);

        /* second.xml을 화면에 보여주는 코드 */
        setContentView(R.layout.second);

        setTitle("Second 액티비티");

        /* second.xml의 돌아기기 버튼을 클릭하면 SecondActivity를 끝내는 코드 */
        Button btnReturn = (Button) findViewById(R.id.btnReturn);
        btnReturn.setOnClickListener(new View.OnClickListener() {
            public void onClick(View v) {
                finish();
            }
        });
    }
}
```

### 내일 일정
* 행궁동 놀러 가기
    - 10시 30분 버스 정류장에서 친구들 만나기