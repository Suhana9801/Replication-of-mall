# Replication-of-mall
This is a test repository to put my 1st year C  project 
#include <stdio.h>
#include <string.h>

void
ret ()
{
  printf ("\nwelcome to our restaurant\n");

  int total = 0, V = 0;
  char ch1;
  printf ("\t\t\t WELCOME TO RESTAURANT");
  printf ("\nTODAY'S MENU");
  do
    {
      int a, b = 100, c = 50, d = 60, e = 60, f = 150, g = 100, h =
	100, i = 60, j = 250, k = 200, l = 150, m = 200, n = 70, o =
	50, p = 99, q = 40, r = 50, s = 70, t = 50, u = 50;
      printf
	("\n1.CHICKEN WINGS\n2.MANCHURIA\n3.CHICKEN 65\n4.CHILLI CHICKEN\n5.MUTTON KHEBAB\n6.SHAHI CHICKEN\n7.CHICKEN BIRYANI\n8.ZAFRANI BIRYANI\n9.PRAWNS BORYANI\n10.MUTTON BIRYANI\n11.CHICKEN NUGLETS\n12.HALEEM\n13.PANEER MASALA WITH RICE\n14.RAJMA CHAVAL\n15.CHEESE NUGLETS\n16.GARLIC BREAD\n17.BROWNIE\n18.RASBEERY PUDDING\n19.ICE CREAM(BUTTERSCOTCH)\n");
      printf ("\n\n---------------------------------------\n");
      printf ("\nWhat do you want to order?\n");
      V++;

      scanf ("%d", &a);

      if (a == 1)
	{
	  printf ("\nCHICKEN WINGS\n");
	  total = b + total;
	}
      if (a == 2)
	{
	  printf ("\nMANCHURIA\n");
	  total = c + total;
	}
      if (a == 3)
	{
	  printf ("\nCHICKEN 65\n ");
	  total = d + total;
	}
      if (a == 4)
	{
	  printf ("\n CHILLI CHICKEN\n ");
	  total = e + total;
	}
      if (a == 5)
	{
	  printf ("\n MUTTON KHEBAB\n ");
	  total = f + total;
	}
      if (a == 6)
	{
	  printf ("\nSHAHI CHICKEN\n ");
	  total = g + total;
	}
      if (a == 7)
	{
	  printf ("\n CHICKEN BIRYANI\n ");
	  total = h + total;
	}
      if (a == 8)
	{
	  printf ("\n ZAFRANI BIRYANI\n ");
	  total = i + total;
	}
      if (a == 9)
	{
	  printf ("\nPRAWNS BIRYANI\n ");
	  total = j + total;
	}
      if (a == 10)
	{
	  printf ("\nMUTTON BIRYANI\n ");
	  total = k + total;
	}
      if (a == 11)
	{
	  printf ("\nCHICKEN NUGLETS\n ");
	  total = l + total;
	}
      if (a == 12)
	{
	  printf ("\nHALEEM\n ");
	  total = m + total;
	}
      if (a == 13)
	{
	  printf ("\nPANEER MASALA WITH RICE\n ");
	  total = n + total;
	}
      if (a == 14)
	{
	  printf ("\n RAJMA CHAVAL\n ");
	  total = o + total;
	}
      if (a == 15)
	{
	  printf ("\nCHICKEN NUGLETS\n ");
	  total = p + total;
	}
      if (a == 16)
	{
	  printf ("\nGALIC BREAD\n ");
	  total = q + total;
	}
      if (a == 17)
	{
	  printf ("\nBROWNIE\n ");
	  total = r + total;
	}
      if (a == 18)
	{
	  printf ("\nRASBERRY PUDDING\n ");
	  total = s + total;
	}
      if (a == 19)
	{
	  printf ("\nICE CREAM(BUTTERSCOTCH)\n ");
	  total = t + total;
	}
      if (a > 19)
	{
	  printf ("\nWRONG INPUT\n");
	}
      printf ("\n Do you want to continue?(y/n)\n");
      scanf ("\n%c", &ch1);

    }
  while (ch1 == 'y');

  if (V == 1)
    printf ("item order");
  else
    printf ("items order");
  printf ("\n\n--------------------------------------\n");
  printf ("\n\n  TOTAL BILL:%d", total);
  printf ("\n\n---------------------------------------\n");
  printf ("\nTHANK YOU\n");

}


void mov ()
{
  char m[100];
  int L, p, o;

  printf ("                      **Welcome to theatre **\n");
  printf ("            which movie you want to watch(enter movie name )\n");
  scanf (" %[^\n]", m);

  printf ("cost per each ticket=250 rupees\n");
  printf
    ("show timings available\n morning show 10:15am press 1\n matinee show 2:15am press 2\n first  show 6:00pm press 3\n second show 9:00 press 4\n ");
  printf ("which show do you want?\n");
  scanf ("%d", &p);


  printf ("number of tickets you want for movie %s\n", m);
  scanf ("%d", &L);

  switch (p)
    {


    case 0:

      {
	printf ("no tickets are purchased\n");
	break;
      }
    case 1:
      {

	printf ("                    *TAKE YOUR TICKET*\n");
	printf ("                            morning show -> 10:15am\n ");
	printf ("                               movie name %s\n", m);
	printf ("                               total cost : %d", 250 * L);
	break;
      }
    case 2:
      {


	printf ("                       *TAKE YOUR TICKET*\n");
	printf ("                              matinee show -> 2:15am \n  ");
	printf ("                                 movie name %s\n", m);
	printf ("                                total cost : %d", 250 * L);
	break;
      }
    case 3:
      {

	printf ("                       *TAKE YOUR TICKET*\n");
	printf ("                               first show -> 6:00pm\n ");
	printf ("                                movie name %s\n", m);
	printf ("                             total cost : %d", 250 * L);
	break;
      }
    case 4:
      {

	printf ("                        *TAKE YOUR TICKET*\n");
	printf ("                                second show -> 9:00am\n ");
	printf ("                                  movie name %s\n", m);
	printf ("                                 total cost : %d", 250 * L);
	break;
      }

    default:
      {
	printf ("at that option no movie timings are available\n");
	printf ("enter correct show time\n");
	scanf ("%d", &p);
      }
    }}
void
ext (char B[10], int Y)
{
  char X[10];
  int E, W;
  printf ("EXIT POINT\n");

  if (Y == 1)
    {
      printf ("\ncar id plz:");
      for (E = 0; E < 100; E++)
	{
	  scanf (" %[^\n]", X);
	  W = strcmp (B, X);
	  if (W == 0)
	    {
	      printf
		("\n                                 you can take your car");
	      printf
		("\n                         **THANKS FOR VISITING OUR MALL***");
	      break;
	    }
	  printf ("enter correct car id");

	}
    }

  else if (Y == 2)
    {
      printf ("enter your bike id\n");
      for (E = 0; E < 100; E++)
	{


	  scanf (" %[^\n]", X);
	  W = strcmp (B, X);
	  if (W == 0)
	    {
	      printf
		(" \n                                you can take your bike\n");
	      printf
		(" \n                           **THANKS FOR VISITING OUR MALL***");
	      break;
	    }

	}
      printf ("enter correct  bike id\n");
    }
  else
    printf
      ("\n                         **THANKS FOR VISITING OUR MALL***");
}
int main ()
{
  int i, k, amount, rem, v, n, q, z, R;
  char name[100], ID[20];
  printf ("                                      WELCOME TO THE MALL*\n");
  printf ("the way you came to the mall??\n");
  printf ("1)  by car enter 1\n");
  printf ("2)  by bike  enter 2\n");
  printf ("3)  by walk enter 3\n");
  scanf ("%d", &n);
  for (i = 0; i <= 5; i++)
    {
      if (i == 5)
	{
	  printf
	    ("since you have attempted many times you are out of program \n ");
	  printf (" *thanks for visiting our mall");

	  return 0;
	}
      switch (n)
	{

	case 1:
	  {

	    printf ("welcome the mall parking slot\n");
	    printf
	      ("since you have came by car you have to  pay the parking bill and receive the receipt\n ");
	    printf ("enter your car ID \n");
	    scanf ("%s", ID);
	    printf ("your id has be saved\n\n");
	    printf ("ENTER YOUR NAME :\n");
	    scanf (" %[^\n]", name);
	    printf ("your name has been recorded \n");
	    printf ("bill to be paid 100rs\n");
	    printf ("enter your amount :");
	    scanf ("%d", &amount);
	    for (R = 0; R < 100; R++)
	      {
		if (amount == 100)
		  break;
		printf (" enter correct amount");
		scanf ("%d", &amount);
	      }

	    printf ("                     your payment is sucessfull*\n");
	    printf ("                        take your parking ticket\n");
	    printf ("                       NAME   : %s\n", name);
	    printf ("                       car ID: %s\n", ID);
	    printf ("                       (100 paid sucessfully)");

	    break;

	  }

	case 2:
	  {
	    printf ("welcome to the mall parking slot\n");
	    printf
	      ("since you have came by bike you have to  pay the parking bill and receive the receipt\n ");
	    printf ("enter your bike ID  \n");

	    scanf ("%s", ID);
	    printf ("your id has be saved\n\n");
	    printf ("ENTER YOUR NAME :\n");
	    scanf (" %[^\n]", name);
	    printf ("your name has been recorded \n");
	    printf ("bill to be paid 50rs\n");
	    printf ("enter your amount :");
	    scanf ("%d", &amount);
	    for (R = 0; R < 100; R++)
	      {
		if (amount == 50)
		  break;
		printf (" enter correct amount:");
		scanf ("%d", &amount);
	      }
	    printf ("                        your payment is sucessfull\n");
	    printf ("                        take your parking ticket\n");
	    printf ("                         NAME   : %s\n", name);
	    printf ("                         bike ID : %s\n", ID);
	    printf ("                         (50 paid sucessfully)");

	    break;
	  }
	case 3:
	  {
	    printf
	      ("since you have came by walk  you can direct visit the mall\n ");
	    break;
	  }
	default:
	  {
	    printf
	      ("you have choosen wrong option once again choose any  onne option \n ");
	    scanf ("%d", &n);
	    continue;

	  }
	}
      if (n == 1)
	{
	  break;
	}
      else if (n == 2)
	{
	  break;
	}
      else if (n == 3)
	{
	  break;
	}
    }



  for (z = 0; z < 100; z++)
    {
      printf ("\nwhere you want to visit\n");

      printf ("enter 1 to visit our restaurant\n");
      printf ("enter 2 to visit our theatre\n");
      printf ("enter 3 to visit our shopping mall\n");
      printf ("enter 4 to exit\n");


      scanf ("%d", &q);
      if (q == 1)
	ret ();
      if (q == 2)
	mov ();
      if (q == 4)
	{
	  ext (ID, n);
	  return 0;
	}

    }
  return 0;
}
