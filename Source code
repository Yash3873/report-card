/*
Author:  Yash Prakash Mhatre
Topic:   Assignment No. 1
Date:    22/04/2023
*/

#include <stdio.h>


int main() {

  char name[20], section;
  int std, maths, eng, hindi, science, ss, totalMarks;

  printf("***********WELCOME************\n");
  puts("Please input the propder information\n");
  printf("Name:");
  scanf("%s", &name);

  printf("Standard:");
  scanf("%d", &std);
  while((getchar())!='\n');

  printf("Section:");
  scanf("%c", &section);

  printf("Enter marks of Maths, English, Hindi, science, ss respectively:");
  scanf("%d%d%d%d%d", &maths, &eng, &hindi, &science, &ss);

  totalMarks = maths+eng+hindi+science+ss;

  puts("-------------------------------------------------\n");
  puts("       Jawahar Navodaya Vidyalaya\n");
  puts("           Annual Report Card\n\n");

  printf("Name:%s\n", name);
  printf("Standard:%d\n", std);
  printf("Section:%c\n\n", section);
  puts("Marks secured out of 100\n");
  printf("Mathematics:%d\nEnglish:%d\nHindi:%d\nScience:%d\nSocialScience:%d\n\n", maths,           eng, hindi, science, ss);
  printf("Total Marks Secured:%d\n", totalMarks);
  usleep(100000);

  if(totalMarks >= 450 && totalMarks <= 500) {
    printf("Grade A");
  } else if(totalMarks >= 400 && totalMarks < 450){
    printf("Grade B");
  } else if(totalMarks >= 350 && totalMarks < 400) {
    printf("Grade C");
  } else if(totalMarks >= 300 && totalMarks < 350) {
    printf("Grade D");
  } else if(totalMarks >= 200 && totalMarks < 300) {
    printf("Grade E");
  } else if(totalMarks >0 && totalMarks < 200) {
    printf("Grade F");
  } else {
    printf("Invalid Marks.");
  }

  return 0;
}
