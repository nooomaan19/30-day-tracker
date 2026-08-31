# 30-day-tracker
My 30-Days self improvement journey and daily progress logs
#include <stdio.h>

void showProgress(int day) {
    printf("\n===========================================\n");
    printf("         DAY %d PROGRESS REPORT             \n", day);
    printf("===========================================\n\n");

    switch(day) {
        case 1:
            printf("[✔] Sleep: Slept well & woke up at 10am\n");
            printf("[✔] Walking: Completed 1238 steps\n");
            printf("[✔] Gym: Hit the gym & felt energized\n");
            printf("[✔] Meals: Ate nutritious food on time\n");
            printf("[✔] Prayers: Completed all 4 prayers\n");
            printf("[✔] Mindset: Staying positive & being better for her\n");
            break;

        case 2:
            printf("[✔] Sleep: Log details here...\n");
            printf("[✔] Walking: Log details here...\n");
            printf("[✔] Gym: Log details here...\n");
            printf("[✔] Meals: Log details here...\n");
            printf("[✔] Prayers: Log details here...\n");
            printf("[✔] Mindset: Log details here...\n");
            break;

        case 3:
        case 4:
        case 5:
        case 6:
        case 7:
        case 8:
        case 9:
        case 10:
        case 11:
        case 12:
        case 13:
        case 14:
        case 15:
        case 16:
        case 17:
        case 18:
        case 19:
        case 20:
        case 21:
        case 22:
        case 23:
        case 24:
        case 25:
        case 26:
        case 27:
        case 28:
        case 29:
        case 30:
            printf("Day %d log will be updated soon! Stay tuned.\n", day);
            break;

        default:
            if(day > 30) {
                printf("Progress log is set for a 30-day journey!\n");
            } else {
                printf("Invalid day! Please enter a number between 1 and 30.\n");
            }
            break;
    }
    printf("\n===========================================\n");
}

int main() {
    int dayNumber;

    printf("Welcome to My 30-Day Self-Improvement Tracker!\n");
    printf("Enter the day number to check progress (1-30): ");

    
    if (scanf("%d", &dayNumber) != 1) {
        printf("\n===========================================\n");
        printf("Invalid input! Please enter a valid number.\n");
        printf("===========================================\n");
        return 1;
    }

    showProgress(dayNumber);

    return 0;
}
