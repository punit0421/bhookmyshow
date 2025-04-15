# bhookmyshow
general dpendencies
implementation 'androidx.appcompat:appcompat:1.3.1'
implementation 'com.google.android.material:material:1.4.0'
implementation 'androidx.constraintlayout:constraintlayout:2.1.0'
implementation 'androidx.legacy:legacy-support-v4:1.0.0'
implementation 'androidx.navigation:navigation-fragment:2.3.5'
implementation 'androidx.navigation:navigation-ui:2.3.5'
implementation 'com.android.support.constraint:constraint-layout:2.0.4'
implementation 'com.google.firebase:firebase-database:20.0.1'
testImplementation 'junit:junit:4.13.2'
implementation 'com.google.firebase:firebase-auth:21.0.1'
implementation 'com.google.android.gms:play-services-auth:19.2.0'
implementation 'androidx.appcompat:appcompat:1.4.0-alpha03'
testImplementation 'junit:junit:4.13.2'
androidTestImplementation 'androidx.test.ext:junit:1.1.3'
androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
implementation 'com.google.android.material:material:1.2.1'
implementation fileTree(dir: 'libs', include: ['*.jar'])

//noinspection GradleCompatible
implementation 'com.android.support:appcompat-v7:23.2.1'

//noinspection GradleCompatible
implementation 'com.android.support:design:23.2.1'
implementation 'com.github.smarteist:autoimageslider:1.4.0'
implementation 'com.facebook.android:facebook-android-sdk:5.15.3'

// Import the BoM for the Firebase platform
implementation platform('com.google.firebase:firebase-bom:28.4.0')
implementation 'com.facebook.android:facebook-login:[8.1)'

// Declare the dependency for the Firebase Authentication library
// When using the BoM, you don't specify versions in Firebase library dependencies
implementation 'com.google.firebase:firebase-auth'
implementation "com.airbnb.android:lottie:3.4.0"
implementation 'com.facebook.android:facebook-android-sdk:[5,6)'
implementation 'com.squareup.retrofit2:retrofit:2.9.0'

// This library is used by retrofit internally to convert json-pojo and pojo-json
implementation 'com.squareup.retrofit2:converter-gson:2.6.1'

//This library is used to observe the API logs, Http status code and the API response
implementation 'com.squareup.okhttp3:logging-interceptor:4.9.0'
implementation 'com.github.bumptech.glide:glide:4.12.0'
annotationProcessor 'com.github.bumptech.glide:compiler:4.12.0'
implementation 'com.pierfrancescosoffritti.androidyoutubeplayer:core:10.0.5'
implementation 'com.borjabravo:readmoretextview:2.1.0'
implementation 'de.hdodenhof:circleimageview:3.1.0'
implementation 'com.jakewharton:butterknife:8.8.1'
