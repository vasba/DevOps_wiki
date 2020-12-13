 # To access sourced variables from other scripts you need to export them also
 source variables_env.sh
 
 export $(cut -d= -f1 variables_env.sh)
