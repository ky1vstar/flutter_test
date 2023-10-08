# Olearis Flutter test

## Goals

Before proceeding to the technical interview, we would like to check you skills as Flutter engineer by providing you with this test task.
Your main goal is to create an app consisting of two screens described below. We expect this app to behave as close as possible to the [demo](https://github.com/ky1vstar/flutter_test/assets/23170237/9cd807f8-3031-49ca-ab9a-9e311ce053c6) video.
Your second goal is to implement the app architecture as it was real project from scratch. You should consider using some architectural patterns (like DDD), state management (like BLoC), localization, etc.

## Sign In screen

1. Create simple sign in form consisting of [logo](resources/logo.svg), login text field, password text field and `Continue` button.
2. Logo should be placed at the top of the screen, `Continue` button at the bottom and text fields should be groupped in the middle.
3. You should handle both portrait and landscape orientations and keyboard appearence making the content scrollable.
4. `Continue` button should have simple validation of non-empty inputs.
5. Try to replicate behaviour shown in [result video](https://github.com/ky1vstar/flutter_test/assets/23170237/9cd807f8-3031-49ca-ab9a-9e311ce053c6) as close as possible.

<img src="https://github.com/ky1vstar/flutter_test/assets/23170237/0283a88c-e425-4f16-9fed-4f1bd8239a8d" width="250">
<img src="https://github.com/ky1vstar/flutter_test/assets/23170237/d26faa06-5302-45ba-a997-034311d19cf6" height="250">

## Home screen

1. Put [logo](resources/logo.svg) image on the screen. It’s minimal margins from each side are 30px and max width is 375.
2. The screen accepts `List<String>` items. The size of the list could be from 0 to any. This list contains the item’s names.
3. You should generate tiles with the items names. Each tile should have minimal margin 12 from each side and a black outside border. There should be two columns.
4. You should calculate tiles width and height to make it: 
    - fill the screen by width;
    - tiles aspect ratio should be 4.
5. The tiles list should be aligned to the bottom. You should use the screen space above it to center Logo vertically and horizontally. See the example below.

<img src="https://github.com/ky1vstar/flutter_test/assets/23170237/5983dc66-fb07-431a-bdfc-5331a2a21add" width="250">
<img src="https://github.com/ky1vstar/flutter_test/assets/23170237/34775aa3-c7e4-43da-9e2e-f5ac8a55227f" width="250">

6. If there are too many items, Logo should be aligned horizontally by it’s minimal margin and a scroll appears. See the example below.

<img src="https://github.com/ky1vstar/flutter_test/assets/23170237/df4953d6-b17b-48c6-9f9d-36b40a54364e)" width="250">
<img src="https://github.com/ky1vstar/flutter_test/assets/23170237/b46fe61b-dfb1-45c3-a369-b454d2cb9e30)" width="250">
<img src="https://github.com/ky1vstar/flutter_test/assets/23170237/c800e05c-0240-4be1-a74a-23b9072f6f14)" width="250">


7. Both portrait and landscape orientations should be handled
8. Try to replicate behaviour shown in [result video](https://github.com/ky1vstar/flutter_test/assets/23170237/9cd807f8-3031-49ca-ab9a-9e311ce053c6) as close as possible.

## Result

https://github.com/ky1vstar/flutter_test/assets/23170237/9cd807f8-3031-49ca-ab9a-9e311ce053c6

