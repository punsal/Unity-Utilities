# Unity-Utilities
 Repository is a folder of utility scripts for Unity projects.

## Publisher Subscriber System

### Classes

* PublisherSubscriber : A static class that responsible to implement Sub-Pub pattern in C#.

* Subscription : A class to mimic token bus for events.

  Use *PublisherSubscriber* class to **Publish** or **Subscribe** events in application. It leverages users to implement loose-coupled event system. I prefer using this pattern with a State Machine.
