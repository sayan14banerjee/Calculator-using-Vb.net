# Calculator-using-Vb.net

This is a basic calculator. you can run it on Microsft Visual Studio Application


# Run The Code
# 1

First dowmload the Microsoft [Visual Studio](https://visualstudio.microsoft.com/downloads/) .....

Then download the [.sln]() file and run it on visual studio...

# 2

open the visual studio 

then create new project type window form and visula basic languge 

then disign the page just like the image 

![this is an image]( )


and set all button like the [.vb]() file....

'''

    Imports System.Windows.Forms.VisualStyles.VisualStyleElement

    Public Class Form1
        Dim value1, value2 As Integer
        Dim operation As String
        Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click
            TextBox1.Text = TextBox1.Text & 1
        End Sub

        Private Sub Button2_Click(sender As Object, e As EventArgs) Handles Button2.Click
            TextBox1.Text = TextBox1.Text & 2
        End Sub

        Private Sub Button3_Click(sender As Object, e As EventArgs) Handles Button3.Click
            TextBox1.Text = TextBox1.Text & 3
        End Sub

        Private Sub Button8_Click(sender As Object, e As EventArgs) Handles Button8.Click
            TextBox1.Text = TextBox1.Text & 4
        End Sub

        Private Sub Button7_Click(sender As Object, e As EventArgs) Handles Button7.Click
            TextBox1.Text = TextBox1.Text & 5
        End Sub

        Private Sub Button6_Click(sender As Object, e As EventArgs) Handles Button6.Click
            TextBox1.Text = TextBox1.Text & 6
        End Sub

        Private Sub Button12_Click(sender As Object, e As EventArgs) Handles Button12.Click
            TextBox1.Text = TextBox1.Text & 7
        End Sub

        Private Sub Button11_Click(sender As Object, e As EventArgs) Handles Button11.Click
            TextBox1.Text = TextBox1.Text & 8
        End Sub

        Private Sub Button10_Click(sender As Object, e As EventArgs) Handles Button10.Click
            TextBox1.Text = TextBox1.Text & 9
        End Sub

        Private Sub Button4_Click(sender As Object, e As EventArgs) Handles Button4.Click
            value1 = TextBox1.Text
            TextBox1.Clear()
            TextBox1.Focus()
            operation = "+"

        End Sub

        Private Sub Button5_Click(sender As Object, e As EventArgs) Handles Button5.Click
            value1 = TextBox1.Text
            TextBox1.Clear()
            TextBox1.Focus()
            operation = "-"
        End Sub

        Private Sub Button9_Click(sender As Object, e As EventArgs) Handles Button9.Click
            value1 = TextBox1.Text
            TextBox1.Clear()
            TextBox1.Focus()
            operation = "*"
        End Sub

        Private Sub Button13_Click(sender As Object, e As EventArgs) Handles Button13.Click
            value1 = TextBox1.Text
            TextBox1.Clear()
            TextBox1.Focus()
            operation = "/"
        End Sub

        Private Sub Button15_Click(sender As Object, e As EventArgs) Handles Button15.Click
            TextBox1.Clear()
            TextBox1.Focus()
        End Sub

        Private Sub Button14_Click(sender As Object, e As EventArgs) Handles Button14.Click
            value2 = TextBox1.Text
            If operation Is "+" Then
                TextBox1.Text = value1 + value2
            ElseIf operation Is "-" Then
                TextBox1.Text = value1 - value2
            ElseIf operation Is "*" Then
                TextBox1.Text = value1 * value2
            Else
                TextBox1.Text = value1 / value2
            End If
        End Sub

        Private Sub Button16_Click(sender As Object, e As EventArgs) Handles Button16.Click
            TextBox1.Text = TextBox1.Text & 0
        End Sub
    End Class



'''
