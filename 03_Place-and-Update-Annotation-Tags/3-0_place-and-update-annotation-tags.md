# Place and Update Annotation Tags

As of Revit 2017, the task of displaying Area Tags in Floor Plans outside of Area Plans \(such as Rentable Areas\) is a manual one. An example of such an application would be an Apartment Building where the total floor area of every Apartment needs to be displayed in addition to room names and dimensions.

Unfortunately, one cannot place an Area Tag in a view other than an Area Plan. Although one can place a Room Tag in an Area Plan, a workflow where the primary plan views are based on Area Plans becomes quite restrictive as the Area Plan View Type does not allow some annotation types such as the call out head to be displayed. Additionally, the Area Boundary Lines themselves can be very annoying.

Many firms resort to a work-around where one places a Generic Annotation Tag in the Floor Plan views and manually updates the Apartment Number and Area. It feels like one is going backwards after adopting a powerful platform like Revit. This chapter is about automating the process of both placing Generic Annotation Tags and updating the same using Dynamo.

