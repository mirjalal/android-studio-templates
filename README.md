# Templates for Android Studio

Both file and live templates will generate a [Kotlin](https://kotlinlang.org/) code for you. All files expanded with a tab.

## How to use file templates*

### [RecyclerView with ListAdapter](/file_templates/recyclerView_with_ListAdapter.vtl) & [RecyclerView with Standard Adapter](/file_templates/recyclerView_with_ListAdapter.vtl)

Click on File menu then navigate to Settings > Editor > File and Code Templates then choose the desired template and fill proper fields.

**[Apache Velocity](http://velocity.apache.org/engine/devel/user-guide.html#Velocity_Template_Language_VTL:_An_Introduction) template language is used.*

## How to use live templates

### [rcvListAdapter](/live_templates/rcvListAdapter)

Create a Kotlin file and give a desired name to it. Type `rcvListAdapter` to generate a class that extends from [ListAdapter](https://developer.android.com/reference/kotlin/androidx/recyclerview/widget/ListAdapter.html) with [DiffUtil](https://developer.android.com/reference/androidx/recyclerview/widget/DiffUtil.Callback.html). Then only proper class namings remain to complete your adapter class.

### [rcvStandardAdapter](/live_templates/rcvListAdapter)

Create a Kotlin file and give a desired name to it. Type `rcvStandardAdapter` to generate a class that extends from [RecyclerView.Adapter](https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView.Adapter). Then only proper class namings remain to complete your adapter class.
