#==============================================================================
          #DATA SCIENCE PORTFOLIO: SIMPLE LINEAR REGRESSION ANALYSIS
              #Topic: Predicting Waist Size Based on Neck Size
#==============================================================================

#NOTE: This analysis requires the 'NeckVsWaist' dataset to be loaded into your 
#global environment before execution.

                      #1.Exploratory Data Visualization
#------------------------------------------------------------------------------
#Generate a scatter plot to visually assess the relationship between the 
#predictor variable (Neck size) and the response variable (Waist size).
plot(
  NeckVsWaist$neck, 
  NeckVsWaist$waist, 
  main = "Neck vs. Waist Size Relationship", 
  xlab = "Neck Size (inches)", 
  ylab = "Waist Size (inches)",
  col  = "darkblue",
  pch  = 16
)


                        #2.Model Fitting & Evaluation
#------------------------------------------------------------------------------
#Fit a simple ordinary least squares (OLS) linear regression model.
NeckWaist.model <- lm(waist ~ neck, data = NeckVsWaist)


                
                  #3.Trend Verification & Statistical Metrics
#------------------------------------------------------------------------------
#Add the fitted linear regression line to the scatter plot in red.
abline(NeckWaist.model, col = "red", lwd = 2)


#Calculate the Multiple R-Squared value (coefficient of determination)
#Formula used: (Correlation Coefficient)^2
r_squared <- cor(NeckVsWaist$neck, NeckVsWaist$waist)^2
print(r_squared)


                            #4.Residual Diagnostics
#------------------------------------------------------------------------------
#on figure a 2x2 multi-panel layout to evaluate regression diagnostic plots.
par(mfrow = c(2, 2))
plot(NeckWaist.model)


#Reset graphical parameters back to a single plot window layout
par(mfrow = c(1, 1))


          #5.statistical summary (coefficients, p-values, F-statistic)
#------------------------------------------------------------------------------
summary(NeckWaist.model)
