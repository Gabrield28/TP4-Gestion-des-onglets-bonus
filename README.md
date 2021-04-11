# TP4-Gestion-des-onglets-bonus
Ex 3 bonus tp4
-----------------------

Question 1
Which subclass of Fragment displays a vertical list of items that are managed by an adapter?

RowsFragment()
PreferenceFragment()
DialogFragment()
ListFragment()

Answer : ListFragment()

-----------------------

Question 2
Which of the following is the best sequence for adding a fragment to an activity that is already running?

Declare the fragment inside the activity's layout file using a <fragment> view.
Declare a location for the fragment inside the activity's layout file using the <FrameLayout> view group.
Declare the location for the fragment inside the activity's layout file using the <FrameLayout> view group, get an instance of the fragment and FragmentManager, and use the add() transaction.
Declare the location for the fragment inside the activity's layout file using the <FrameLayout> view group. Then get an instance of the fragment and FragmentManager, begin a transaction, use the add() transaction, and commit the transaction.

Answer : 
Declare the location for the fragment inside the activity's layout file using the <FrameLayout> view group. Then get an instance of the fragment and FragmentManager, begin a transaction, use the add() transaction, and commit the transaction.

-----------------------

Question 3

Question 3
Which statement gets a reference to a fragment using the fragment's layout resource?

fragment = new SimpleFragment();
SimpleFragment fragment = (SimpleFragment) fragmentManager.findViewById(R.id.fragment_container);
SimpleFragment fragment = (SimpleFragment) fragmentManager.findFragmentById(R.id.fragment_container);
FragmentTransaction fragmentTransaction = fragmentManager.beginTransaction();

Answer :
fragment = new SimpleFragment();
