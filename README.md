# TRSPO_lab2
System for student testing:

User Management Service:
https://github.com/MakTsy/TRSPO_user_management

Test Management Service:
https://github.com/MakTsy/TRSPO_test_management

Test Passing Service:
https://github.com/MakTsy/TRSPO_test_passing

Test Report Service:
https://github.com/MakTsy/TRSPO_test_report



NOTE:
There is a file "general_workloads.yaml" in the Test Management Service repo.

You can use it to run a project



Commands:

RUN:

minikube start

kubectl apply -f general_workloads.yaml


CHECK_IP:

echo "$(minikube ip)"


TURN_OFF:

minikube stop && minikube delete



Service ports:

User Management Service: 31000

Test Management Service: 31002

Test Passing Service: 31001

Test Report Service: 31004
