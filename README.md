# Orquestra-de-cont-ineres-go
package main

import (
    "context"
    "fmt"
    "log"

    metav1 "k8s.io/apimachinery/pkg/apis/meta/v1"
    "k8s.io/client-go/kubernetes"
    "k8s.io/client-go/rest"
)

func main() {
    // Crie um cliente Kubernetes
    config, err := rest.InClusterConfig()
    if err != nil {
        log.Fatal(err)
    }
    clientset
    
