# updating

    Code
      decision_tree(cost_complexity = 0.1) %>% set_engine("rpart", model = FALSE) %>%
        update(cost_complexity = tune(), model = tune())
    Output
      Decision Tree Model Specification (unknown)
      
      Main Arguments:
        cost_complexity = tune()
      
      Engine-Specific Arguments:
        model = tune()
      
      Computational engine: rpart 
      

