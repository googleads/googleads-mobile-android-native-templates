apply plugin: 'com.android.library'

android {
    compileSdkVersion 30

    defaultConfig {
        minSdkVersion 16
        targetSdkVersion 30
        versionCode 2
        versionName "1.1"

        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"

    }

    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pgcfg'
            consumerProguardFiles 'proguard-rules.pgcfg'
        }
    }

    lintOptions {
        resourcePrefix 'gnt_'
    }
}



dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar'])
    implementation 'androidx.appcompat:appcompat:1.2.0'
    testImplementation 'junit:junit:4.13.1'
    androidTestImplementation 'androidx.test:runner:1.3.0'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.3.0'
    implementation 'com.google.android.gms:play-services-ads:20.1.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.0.4'
    implementation 'com.google.errorprone:error_prone_annotations:2.16'
}
